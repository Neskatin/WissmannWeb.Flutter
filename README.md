# WissmannWeb Flutter Essentials - Extension Pack for VS Code

[![Badge for version for Visual Studio Code extension Wissmann-Web.wissmannweb-flutter](https://vsmarketplacebadge.apphb.com/version/Wissmann-Web.wissmannweb-flutter.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-flutter) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Wissmann-Web.wissmannweb-flutter.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-flutter) [![Rating](https://vsmarketplacebadge.apphb.com/rating-star/Wissmann-Web.wissmannweb-flutter.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-flutter) [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)

This extension pack for Visual Studio Code adds extensions that are amazingly useful for Flutter development.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

> As tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Here are some of my recommended settings. These are optional, but I get asked a lot for them, so here they are.

### Editor settings

```json
  "workbench.colorTheme": "Default Light+",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",

  "editor.renderIndentGuides": false,
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": false,
  "editor.minimap.enabled": false,
  "editor.renderWhitespace": "none",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "off",

  "npm.packageManager": "yarn"

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
```

### Prettier settings

```json
  "prettier.singleQuote": true,
  "prettier.printWidth": 140,
```

### Todo Tree settings

```json
  "todo-tree.filtering.excludeGlobs": [
    "**/node_modules/**",
    "**/dist*/**"
  ],
  "todo-tree.tree.flat": true,
```

## Included

Here is the list of extensions the pack includes:

- [WissmannWeb.Editor](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-editor) - My prefered VS Code Editor extentions.
- [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter) - Flutter support and debugger for Visual Studio Code
- [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code) - Dart language support and debugger for Visual Studio Code
- [bloc](https://marketplace.visualstudio.com/items?itemName=FelixAngelov.bloc) - Support for the bloc library and provides tools
