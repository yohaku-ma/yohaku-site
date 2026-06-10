# yohaku 簡易公開手順

このファイルは、GitHub Pagesで公開するための実行手順です。

---

## 1. GitHubで新しいリポジトリを作成

リポジトリ名の例：

```text
yohaku-site
```

公開設定は、最初は `Public` で問題ありません。

---

## 2. このフォルダの中身をアップロード

アップロードするのは、`yohaku-site-next-step` フォルダそのものではなく、  
その中に入っている以下のファイル・フォルダです。

```text
index.html
404.html
.nojekyll
robots.txt
css/
js/
assets/
README.md
PUBLISH_GUIDE.md
LAUNCH_CHECKLIST.md
```

---

## 3. GitHub Pagesを有効化

GitHub上で以下の順番に進みます。

```text
Settings
→ Pages
→ Build and deployment
→ Source：Deploy from a branch
→ Branch：main
→ Folder：/root
→ Save
```

---

## 4. 数分待ってURLを確認

しばらくすると、GitHub PagesのURLが表示されます。

例：

```text
https://ユーザー名.github.io/yohaku-site/
```

このURLを開いて、サイトが表示されれば公開完了です。

---

## 5. 公開後に確認すること

- First Viewが崩れていないか
- スマホで文字が読みやすいか
- Concept Works画像が表示されているか
- Concept Sheetが表示されているか
- メールボタンが正しい宛先になっているか
- Instagramリンクが正しいか
- LINEやSNSでURLを送った時にOGP画像が表示されるか

---

## 6. 後で写真を差し替える場合

写真を送った後、以下の画像を差し替えます。

```text
assets/images/common/hero_yohaku_01.jpg
assets/images/about/about_profile_01.jpg
assets/images/about/about_work_01.jpg
```

HTML側の画像パスも、そのタイミングで正式画像に変更します。
