# textareaHighlighter
テキストエリア内で特定文字列をハイライト

## 仕様
- 利用禁止用語が入力された自伝でアラートメッセージを表示し、対象文字列をハイライトする。
- 初期表示、JS(ボタンクリック)で値が挿入された時も同様
- テキストエリアはリサイズを禁止し、入力内容に応じてheightを調整する

## jQuery highlightTextarea
https://garysieling.github.io/jquery-highlighttextarea/

便利なライブラリがあるが、キー操作、マウス操作のみの対応で、
初期表示やJSで値を挿入するタイミングでイベントを発火できなかったため、
自前で実装した。

※他にも調べればあるようでした。
https://github.com/marexandre/jquery.textarea-highlighter.js
