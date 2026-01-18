## hm-javascript-localStorage

Hello Mentor の課題で制作した、JavaScript の localStorage を使用したテーマ切り替えのサンプル実装です。

🔗 デモURL
https://keibpm420.github.io/hm-javascript-localStorage/

### 概要

ボタンをクリックすることでライトモード／ダークモードを切り替え、
選択したテーマを localStorage に保存します。
ページを再読み込みしても、前回選択したテーマが保持されます。

### 実装内容

-   ボタン操作によるテーマ（ライト／ダーク）の切り替え
-   `isDarkMode` の状態を localStorage に保存
-   ページ読み込み時に localStorage の値を参照してテーマを復元

### 仕様

-   localStorage のキー名：`isDarkMode`
-   保存される値：`true` / `false`（文字列）
-   ダークモード時は `body` に `dark-mode` クラスを付与
-   ボタンの文言は現在のテーマに応じて切り替わる

### 使用目的

localStorage を使った状態管理と、
ページ再読み込み後も状態を保持する仕組みを理解するための学習用実装です。
