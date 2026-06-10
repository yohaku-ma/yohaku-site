# yohaku GitHub Pages 公開ガイド

## 1. 事前確認

公開前に以下を差し替えてください。

- `index.html` 内の `uki182001@gmail.com`
- `index.html` 内の `https://www.instagram.com/emu_yu_/`
- First View画像を正式画像へ差し替える場合は `assets/images/common/hero_yohaku_01.jpg` を追加し、HTMLの画像パスを変更
- About用画像を正式画像へ差し替える場合は `assets/images/about/` に追加し、HTMLの画像パスを変更

## 2. GitHubにアップロードするファイル

このフォルダ `yohaku-site/` の中身を、GitHubリポジトリのルートにアップロードします。

重要なファイル：

```text
index.html
404.html
.nojekyll
robots.txt
css/style.css
js/script.js
assets/
README.md
```

## 3. GitHub Pages設定

おすすめは、`main` ブランチのルート `/` から公開する方法です。

設定の流れ：

```text
Repository
→ Settings
→ Pages
→ Build and deployment
→ Source: Deploy from a branch
→ Branch: main
→ Folder: /root
→ Save
```

## 4. 公開後の確認

公開後、以下を確認します。

- First Viewが崩れていないか
- スマホで文字が大きすぎないか
- Concept Works画像が表示されるか
- Concept Sheetが表示されるか
- メールリンクが正しいか
- Instagramリンクが正しいか
- OGP画像が表示されるか
- 404ページが表示されるか

## 5. 今後の更新方法

HTMLを直す場合：

```text
index.html
```

デザインを直す場合：

```text
css/style.css
```

画像を差し替える場合：

```text
assets/images/
```

を編集します。
