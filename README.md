# MORIPOWER — 人気の猫の種類

HTML・CSS・画像だけで動く、GitHub Pages向けのサイトです。

## ブラウザーから公開する手順

1. GitHubで「New repository」を選び、好きなリポジトリ名（例：moripower）でPublicのリポジトリを作成します。
2. 「uploading an existing file」または「Add file → Upload files」を開きます。
3. 次のファイルをすべて同じ階層（リポジトリの一番上）にアップロードして「Commit changes」を押します。
   - index.html
   - style.css
   - cat01.png
   - cat02.png
   - cat03.png
   - cat04.png
   - .nojekyll（HTMLをそのまま配信するための空ファイル）
   - README.md（この説明書・任意）
4. リポジトリの「Settings → Pages」を開きます。
5. 「Build and deployment」で次の設定を選び、「Save」を押します。
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)
6. 公開処理が完了したら、同じPages画面に表示されるURLを開きます。

通常の公開URLは https://ユーザー名.github.io/リポジトリ名/ です。
main以外のブランチにアップロードした場合は、そのブランチを指定してください。
更新するときは、同じファイルをアップロードして変更を保存します。

## 公開用ZIPを使う場合

github-pages.zipには公開用ファイルが入っています。解凍して、中のファイルをアップロードしてください。
ZIPファイルそのものをアップロードしてもサイトにはなりません。
デザイン01.pngとデザイン02.pngは見本のため、公開には不要です。

## お問い合わせフォームについて

現在は入力と必須項目チェックのみ対応しています。実際の送信には別途フォームサービスなどの接続が必要です。
会社概要・採用は表示のみです。リンク先が用意できたらindex.htmlで設定してください。

## 公式の説明

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
