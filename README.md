# STM32_DEV

引き継ぎ用のドキュメントです

現在執筆中です

## リポジトリの構造について

- 目次のページ以外はDocument/講座種類/タイトル/html・pngファイル、という階層にしてあります

- 追加したいときは、適切な講座種類のフォルダ直下に講座のフォルダを作成してください

### ファイル構造

- Documents
  - Setup
    - 01_install
      - 01_install.html
      - STM32.png
      - TeraTerm.png
  - Basic
  - Advance
  - Dev
  - Task
  - Supplement
  - Test
  - Format.css

- index.html
- STM32.png
- README.md


## ドキュメントの修正について

- GitHubのIssueに投げてくれるとそのうち対応します

## 保守管理関係のお話

- もし引き継ぐことになった場合はここを読んでね

### 既知の問題点

- ICM45686評価ボードが品薄（そもそも生産数が少ない）
  - 新しいセンサーに移行する場合は応用・発展編の修正が必要

- 命名規則がぐちゃぐちゃ
  - 関数はパスカルケース(GetDataなど)、変数はスネークケース(accel_dataなど)がよさそう