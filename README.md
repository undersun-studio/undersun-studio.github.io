# Undersun.Studio public site

アプリ審査と利用者サポートのための公開専用静的サイトです。個人メモやアプリ本体のソースコードは含めません。

## 公開パス

- `/anohitozukan/privacy/`
- `/anohitozukan/support/`
- `/denkencbt/privacy/`
- `/denkencbt/terms/`
- `/denkencbt/support/`

## GitHub Pages公開手順

1. `undersun-studio-site` などの公開リポジトリへ、このフォルダの内容だけをpushする。
2. GitHub Pagesを`main`ブランチのルートから公開する。
3. `undersun.studio`を取得し、GitHub Pages指定のDNSレコードを登録する。
4. リポジトリのルートに、`undersun.studio`だけを記載した`CNAME`を追加する。
5. `support@undersun.studio`の受信またはメール転送を設定し、各ページの連絡先を現在の暫定アドレスから変更する。
6. 全ページがログインなしのHTTPSで開けることを確認する。
