# 心電図メモ

24時間心電図（ホルター心電図）の記録用、個人向けのシンプルなWebアプリです。

## GitHub Pagesで使う

1. GitHubで新しいリポジトリを作成
2. `index.html` をアップロード
3. Settings → Pages
4. Deploy from a branch → `main` / `root` を選択
5. 発行されたURLをiPhoneのSafariで開く

記録はブラウザの `localStorage` に保存されます。
CSV保存で記録をファイルとして取り出せます。

※病院から指定された記録方法がある場合は、そちらを優先してください。
