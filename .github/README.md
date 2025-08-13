# &#x1f388; URL
https://fuka161cm.github.io/

# 使用ツール
- ドキュメント変換ツール
  - [Pandoc](https://pandoc.org/)
- クラスレスCSSフレームワーク
  - [Water.css](https://watercss.kognise.dev/)

# 変換手順覚書
1. resume.md に変更を加える 
2. resume.md を index.html に変換<br>
  `pandoc docs/resume.md -o docs/index.html`
3.  生成された index.html 内に`<head>`タグを追加してCSSリンクを配置
