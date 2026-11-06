# Fecuw Portfolio

HTMLとCSSで作った、GitHub Pages用のポートフォリオです。

```text
index.html                 ポートフォリオの入口
style.css                  入口のCSS
assets/nitech-preview.png  作成物一覧のサムネイル
made/
  nitech/
    index.html             元のNITech Area Guide
    style.css              ガイドのCSS
```

入口の「作成物一覧」から `made/nitech/index.html` を開けます。
ガイド上部の「ポートフォリオに戻る」から入口へ戻れます。

## 作成物を追加する

1. `made/` の中に作成物のフォルダを作り、HTMLやCSSを配置します。
2. 入口の `index.html` にある `<article class="work">` を複製します。
3. リンク先、画像、タイトル、説明を書き換えます。

ビルドやnpmパッケージは不要です。入口はHTMLとCSSのみで表示されます。
NITech Area Guideは従来どおりBootstrap、Leaflet、外部画像、地図タイルをネットワーク経由で読み込みます。

GitHub Pagesはリポジトリのルートを公開元に指定してください。
