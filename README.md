# 一問一図 制作ツール ポリシーページ

YouTube チャンネル「一問一図」（@ichimonichizu）の制作ツールが使う Google OAuth 同意画面のための、ホームページ・プライバシーポリシー・利用規約です。GitHub Pages で配信します。

| ページ | ファイル | 同意画面の項目 |
|---|---|---|
| ホーム | `index.html` | アプリのホームページ |
| プライバシーポリシー | `privacy.html` | アプリのプライバシーポリシーのリンク |
| 利用規約 | `terms.html` | アプリの利用規約のリンク |

スコープや扱うデータを変えたら（本体の `pipeline/src/youtube.ts` の `SCOPES` など）、`privacy.html` の内容と最終更新日も直すこと。
