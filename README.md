# キミシダイ日記 — 利用規約・プライバシーポリシー

App Store Connect に登録する公開ページ。GitHub Pages で配信する。

## このリポジトリのHTMLは手で編集しないこと

`index.html` / `privacy.html` / `terms.html` は自動生成物。出典はアプリ本体の

    src/constants/legalDocuments.ts

ここを直さないと、アプリ内表示と公開ページの文面がズレる。文言を変えるときは
アプリ側のリポジトリで次を実行し、生成された3枚をここにコピーして push する。

    node scripts/build-legal-pages.mjs
