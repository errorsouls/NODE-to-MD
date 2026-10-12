NODE to MD

A lightweight, browser-based visual node editor for organizing ideas, features, and their relationships into AI-readable Markdown.

機能やアイデアをノードで視覚的に整理し、AIが読み取りやすいMarkdown形式に変換するWebツールです。

Try NODE to MD / ブラウザで使う

"日本語版を開く / Japanese" (https://errorsouls.github.io/NODE-to-MD/)

"Open English Version / 英語版" (https://errorsouls.github.io/NODE-to-MD/editor-en.html)

上記のリンクからブラウザ上で直接利用できます。インストールは不要です。

You can use NODE to MD directly in your browser using the links above. No installation required.

Features / 機能

- Create and edit feature blocks / ブロックの作成・編集
- Connect blocks to represent relationships / ブロック間の接続
- Add tags to connections / 接続へのタグ付け
- Search and highlight connected blocks / 接続関係の検索・ハイライト
- Import and export Markdown / Markdownの読み込み・出力
- Pan and zoom the canvas / キャンバスの移動・拡大縮小
- Runs entirely in your browser / ブラウザ内で動作

Usage / 使い方

1. Add blocks and enter their names and descriptions. / ブロックを追加して名前と説明を入力します。
2. Connect related blocks and optionally add tags. / 関連するブロックを接続し、必要に応じてタグを付けます。
3. Use Search to highlight relationships. / 検索機能で接続関係を確認します。
4. Export your design as Markdown. / 設計内容をMarkdownとして出力します。
5. Load the exported Markdown to continue editing. / 出力したMarkdownを読み込んで編集を再開できます。

Languages / 対応言語

- "editor-jp.html" — Japanese / 日本語版
- "editor-en.html" — English / 英語版

Markdown Format / 出力形式

The exported Markdown contains feature names, descriptions, relationships, optional tags, and editor positions.

出力されるMarkdownには、各ブロックの名前・説明・接続関係・タグ・配置情報が含まれます。

Connections are undirected and do not imply execution order. Block positions are used only to restore the editor layout and are not part of the implementation requirements.

接続に方向や実行順序の意味はありません。配置情報はエディタ上の位置を復元するためのもので、実装仕様には含まれません。

Notes / 注意事項

- No installation or server-side processing is required. / インストールやサーバー側の処理は不要です。
- Work is not automatically saved. Export your Markdown before closing the page. / 作業内容は自動保存されません。ページを閉じる前にMarkdownを出力してください。
- This tool is intended for high-level design organization, not automatic implementation. / 本ツールは概要設計の整理を目的としており、実装を自動化するものではありません。

License / ライセンス

WTFPL (Do What The Fuck You Want To Public License).

See the "LICENSE" file for details.
