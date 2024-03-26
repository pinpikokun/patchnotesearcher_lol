# PatchNoteSearcher
![image](https://github.com/Shounen-Bob/patchnotesearcher_lol/assets/164868616/84d125a3-d3cf-476a-bba0-bd11c8d14fd9)
# できること
- 入力したチャンピオン名またはアイテム名に関連する修正をS14.1パッチから遡って表示します
- 最新パッチの修正のみでなく、S1開始から4今までに適用された修正を履歴にように表示できます。
  
# 実行する内容
- patchnote.txtにあるURL（LoLJPサーバーのパッチノートURLを想定）のhtmlをそれぞれ取得
- 検索ワードを入力すると、上で取得したURLから該当の見出しを検出しパッチ修正内容を表示する
  - ヴォイド勢の名前が記号無しで入力されたら正しい表記に修正する（例：カイサ⇒カイ＝サ）
# 動作に必要なセットアップ(2024/03/25)
- patchnote.txtにURLを入れる。現時点ではS14のものしかありません
- patchnote.txtをpyと同じディレクトリに格納しないと動きません
