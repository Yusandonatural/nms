# NATURAL MATCHA STANDARD — site

GitHub Pages 用の静的サイト。

## デプロイ手順
1. GitHub で新しいリポジトリを作成（例: `nms-site`）
2. このフォルダの中身をすべてリポジトリのルートにアップロード（Add file → Upload files）
3. Settings → Pages → Source: `Deploy from a branch` / Branch: `main` / `/ (root)` → Save
4. 数分後 `https://<ユーザー名>.github.io/nms-site/` で公開

## ページ
- index.html — トップ
- matcha.html — 自然抹茶
- sado.html — 自然茶道
- chaji.html — 自然茶事

## 写真の差し替え
`assets/` 内の jpg を同名で上書き。ドラッグ＆ドロップ枠（image-slot）はブラウザ内での仮置きなので、公開版では `<img>` に置き換えるか、写真確定後に再書き出しが必要。
