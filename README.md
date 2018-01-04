
My VS Code Settings
-------------------

**plugin:**
 1. ApiDoc Snippets
 2. Document This
 3. ESLint
 4. Seti-theme
 5. vscode-icons

**font**:
Microsoft Yahei Mono ([download link](https://github.com/Microsoft/vscode/files/555425/yahei_mono.zip))

**vs code settings**
{
    "editor.tabSize": 2,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "window.menuBarVisibility": "toggle",
    "workbench.iconTheme": "vscode-icons",
    "window.zoomLevel": -1,
    "editor.minimap.enabled": true,
    "workbench.colorTheme": "Seti",
    "editor.fontSize": 16,
    "editor.fontFamily": "'Microsoft Yahei Mono'",
    "editor.lineHeight": 24
}

**JSLint settings** (.eslintrc)
{
  "extends": "eslint:recommended",
  "env": {
    "es6": true,
    "node": true,
    "mocha": true
  },
  "parserOptions": {
    "ecmaVersion": 2017,
    "sourceType": "module"
  },
  "rules": {
    "no-console": "off",
    "indent": ["error", 2]
  }
}
