# markdown-html

単一のHTMLファイルでmarkdownを表示するテンプレート

## 参考資料
* 元ネタ
    * [そろそろExcelで資料作るのやめたい - Qiita](https://qiita.com/tatesuke/items/794a7f97ae217daba25b)
* 利用ライブラリ
    * [GitHub - markedjs/marked: A markdown parser and compiler. Built for speed.](https://github.com/markedjs/marked)
    * [GitHub - highlightjs/highlight.js: JavaScript syntax highlighter with language auto-detection and zero dependencies.](https://github.com/highlightjs/highlight.js)
    * [GitHub - mermaid-js/mermaid: Generation of diagram and flowchart from text in a similar manner as markdown](https://github.com/mermaid-js/mermaid)
    * [GitHub - sindresorhus/github-markdown-css: The minimal amount of CSS to replicate the GitHub Markdown style](https://github.com/sindresorhus/github-markdown-css)

## オフライン環境で利用する場合
```sh
$ npm install -g inline-source-cli
$ inline-source --compress markdown.html markdown-offline.html
```
