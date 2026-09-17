# YUGURE studio website

GitHub Pages 用の静的サイトです。リポジトリ名を `YUGURE-studio.github.io` とし、このフォルダの中身をリポジトリ直下に置いてください。GitHub の Settings → Pages で `Deploy from a branch`、`main`、`/(root)` を選ぶと、`https://yugure-studio.github.io/` で公開できます。

公開前に確認すること:

- `contact/index.html`: 公開用メールアドレスへの受信を確認する。
- `apps/otta/privacy/index.html`: 実装・Google Play のデータ セーフティ申告・アプリ内説明と一致するか最終確認する。
- `apps/otta/account-deletion/index.html`: アプリの削除依頼コード機能とサーバー側の削除手順を検証してから公開する。
- `apps/otta/terms/index.html`: アプリ内規約との整合と提供条件を最終確認する。
- `apps/otta/index.html`: 提供状況が確定したら更新する。

アプリの配布開始前に、削除依頼コードの発行・メール受付・サーバー側削除手順を実機で確認してください。
