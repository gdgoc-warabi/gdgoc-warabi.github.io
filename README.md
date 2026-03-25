# docs

GitHub Pages で公開するドキュメント一式です。

## 公開構成

- ルート: `index.html`
- 規約ページ: `sync/terms.html`
- プライバシーポリシー: `sync/privacy-policy.html`

公開 URL（プロジェクトページ）:

- <https://gdgoc-warabi.github.io/>

## GitHub Pages 設定

GitHub リポジトリの `Settings` -> `Pages` で以下を設定します。

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

設定後、反映まで数十秒から数分かかる場合があります。

## ローカル確認

静的ファイルのみなので、任意のローカルサーバーで確認できます。

例（Python）:

```bash
python -m http.server 8000
```

その後、`http://localhost:8000/` を開いて表示を確認してください。
