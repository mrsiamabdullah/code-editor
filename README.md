<h1>My VS Code Settings</h1>

```
{
  "editor.fontLigatures": true,
  "editor.fontWeight": "350",
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
  // cursor
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "phase",
  // config related to code formatting ---
  "editor.formatOnSave": true,
  "[javascriptreact]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.fixAll.tslint": "explicit",
    "source.organizeImports": "explicit"
  },
  "vscode_custom_css.imports": [
    "file:///c:/Users/siama/.vscode/extensions/brandonkirbyson.vscode-animations-2.0.1/dist/updateHandler.js"
  ],
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.alwaysShowStatus": true,
  //terminal
  "terminal.integrated.fontSize": 15,
  "terminal.integrated.fontWeight": "400",
  "terminal.integrated.fontFamily": "Fira Code, Operator Mono",
  // terminal customization
  "workbench.colorCustomizations": {
    "terminal.background": "#1D2021",
    "terminal.foreground": "#A89984",
    "terminalCursor.background": "#A89984",
    "terminalCursor.foreground": "#A89984",
    "terminal.ansiBlack": "#1D2021",
    "terminal.ansiBlue": "#0D6678",
    "terminal.ansiBrightBlack": "#665C54",
    "terminal.ansiBrightBlue": "#0D6678",
    "terminal.ansiBrightCyan": "#8BA59B",
    "terminal.ansiBrightGreen": "#95C085",
    "terminal.ansiBrightMagenta": "#8F4673",
    "terminal.ansiBrightRed": "#FB543F",
    "terminal.ansiBrightWhite": "#FDF4C1",
    "terminal.ansiBrightYellow": "#FAC03B",
    "terminal.ansiCyan": "#8BA59B",
    "terminal.ansiGreen": "#95C085",
    "terminal.ansiMagenta": "#8F4673",
    "terminal.ansiRed": "#FB543F",
    "terminal.ansiWhite": "#A89984",
    "terminal.ansiYellow": "#FAC03B"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.iconTheme": "vscode-icons",
  "editor.fontSize": 16,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.stickyScroll.scrollWithEditor": false,
  "eslint.run": "onSave",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.smoothScrolling": true,
  "editor.stickyScroll.enabled": false,
  "workbench.list.smoothScrolling": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "git.openRepositoryInParentFolders": "never",
  "code-runner.clearPreviousOutput": true,
  "code-runner.showExecutionMessage": false,
  "output.smartScroll.enabled": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontFamily": "Operator Mono, 'Fira Code'",
  "cSpell.language": "en,lorem,en-GB,en-US",
  "cSpell.userWords": ["Redmi"],
  "workbench.colorTheme": "GitHub Dark"
}
```
