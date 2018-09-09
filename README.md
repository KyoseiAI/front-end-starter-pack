# Front-End Starter Pack
本擴充功能集包含零基礎的前端初學者在設計「靜態網頁」時最需要用到的基礎擴充功能，收錄常用的各種自動提示的相關擴充功能。詳細內容請參閱下表：



## 編輯器加強
|擴充功能名稱|功能| 
|---|---|
|[Sublime Text Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)|Sublime Text的鍵盤快速鍵對應|
|[Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)|讓vscode加入對HTML, CSS, JS, JSON的支援|
|[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)|提供路徑的自動提示與補全|

## 程式碼自動提示
|擴充功能名稱|功能| 
|---|---|
|[IntelliSense for CSS class names](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)|提供css檔中的類別名稱自動提示|
|[Bootstrap 4 & Font awesome Snippets](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)|提供Bootstrap 4 範例程式碼與 Font awesome的自動提示與補全|
|[jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)|提供130個常用的 jQuery 範例程式碼|


## 錯誤訊息提示
|擴充功能名稱|功能| 
|---|---|
|[jshint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint)|整合 JSHint 到VS Code中 讓編輯器可以針對程式碼做提示|
|[stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)|整合 CSS/SCSS/LESS的linter 到VS Code中 讓編輯器可以針對CSS程式碼做提示|

## 註解功能加強
|擴充功能名稱|功能| 
|---|---|
|[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)|在註解中加入待辦事項|
|[VS Code CSS Comments](https://marketplace.visualstudio.com/items?itemName=ashhitch.vs-code-css-comments)|加強CSS中的註解功能，可以自動產生一些漂亮的註解格式|


## 網頁預覽
|擴充功能名稱|功能| 
|---|---|
|[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)|讓vscode打開瀏覽器即時預覽網頁|


## 建議的編輯器設定
初學者可以套用的編輯器設定，請參考以下設定
```javascript
{
    "editor.formatOnSave": true,
    "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace",
    "emmet.triggerExpansionOnTab": true,
    "emmet.showExpandedAbbreviation": "always",
    "emmet.showAbbreviationSuggestions": true,
    "stylelint.enable": true,
    "css.validate": false,
    "scss.validate": false
}
```