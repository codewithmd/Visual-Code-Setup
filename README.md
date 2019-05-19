# Visual-Code-Setup


### Theme

I use the `Dracula` theme with the dimmed bg option. [Link &rarr;](https://draculatheme.com/visual-studio-code/)

### My Extensions

For each of the extensions, read the overview page in order to learn how to use it.

`Javascript Console Utils` to make easy console.log() with a short-cut key. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=whtouche.vscode-js-console-utils)

`Live Server` It provides a development local server for static/dynamic pages. [Link &rarr;](https://github.com/ritwickdey/vscode-live-server/blob/master/docs/settings.md)

`Auto Close Tag` to automatically close HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

`Auto Rename Tag` to automatically change matching HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

`Color Highlight` to, as the name says, highlight colors in CSS. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

`Paste and Indent` to automatically indent pasted code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)

`Path Intellisense` to autocomplete filenames. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

`Prettier` to automatically format code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

`Material Icon Theme` to make the Icons looks amazing. [Link &rarr;](https://github.com/PKief/vscode-material-icon-theme)

### Other extensions I use (will keep it updated) 

`Project Manager` to easily switch between projects. One of the most useful extensions. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

### Settings

If you want your editor to work and look exactly the same way as mine, you can copy these settings to your own settings file. Just go to settings in VSCode, and on the right side, you can paste this code.

```
{
    "editor.fontSize": 16,
    "files.autoSave": "onFocusChange",
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "workbench.statusBar.visible": true,
    "workbench.activityBar.visible": true,
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "liveServer.settings.donotShowInfoMsg": true,
    "window.zoomLevel": 0,
    "editor.tabSize": 2,
    "workbench.iconTheme": "material-icon-theme",
    "files.trimFinalNewlines": true,
    "workbench.colorCustomizations": {
        "statusBar.background": "#035497",
        "statusBar.noFolderBackground": "#34495e",
        "statusBar.debuggingBackground": "#33393b75",
        "tab.activeBackground": "#4f626d",
        "tab.activeForeground": "#fffdfd",
    },
    "css.validate": false,
    "scss.validate": false,
    "less.validate": false,
    "editor.wordWrap": "on",
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "workbench.colorTheme": "Dracula",
    "editor.fontWeight": "300",
    "editor.fontLigatures": true,
    "editor.fontFamily": "'Fira Code',Consolas, 'Courier New', monospace",
    "files.associations": {
        "*.scss": "scss"
    },
}
```
### Code Snippets

Here I have add some code snippets to code faster in Javascript. if you are also working in Javascript then you may try this out.
It's like emmet for HTML/CSS. You just add some short-cut and when you type that short-cut and hit ` TAB ` Your custon code will show there. You can even customize.. 

Yes there is a little learning curv that how to edit these stuffs just google ( ` How to customize code snippets in vs code ?` ) it you will find lots of tutorials online out there.

```
{
  // Place your snippets for javascript here. Each snippet is defined under a snippet name and has a prefix, body and
  // description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
  // $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the
  // same ids are connected.
  // Example:
  // "Print to console": {
  // 	"prefix": "log",
  // 	"body": [
  // 		"console.log('$1');",
  // 		"$2"
  // 	],
  // 	"description": "Log output to console"
  // }

  "Print to console": {
    "prefix": "cl",
    "body": [
      "console.log($1);"
    ],
    "description": "Log into console"
  },
  "Named Function": {
    "prefix": "nfn",
    "body": [
      "function ${1:someName}($2){",
      "  $3",
      "}"
    ],
    "description": "Named Function"
  },
  "Arrow Functon": {
    "prefix": "afn",
    "body": [
      "const ${1:functionName} = ($2) => {",
      "  $3",
      "}"
    ],
    "description": "Arrow Functon"
  },
  "Function Expression": {
    "prefix": "efn",
    "body": [
      "const ${1:functionName} = function($2) {",
      "  $3",
      "}"
    ],
    "description": "Function Expression"
  }
}
```