# &#x1f388; URL
https://fuka161cm.github.io/

# 使用ツール
- ドキュメント変換ツール
  - [Pandoc](https://pandoc.org/)
- クラスレスCSSフレームワーク
  - [Water.css](https://watercss.kognise.dev/)

# 変換手順覚書
1. resume.md を index.htmlに変換<br>
  `pandoc resume.md -o index.html`
2.  生成された index.html 内に`<head>`タグを追加し、CSSリンクを配置