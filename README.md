# Environment Setups

1. [VS Code Global Level User Setting](#vs-code)
   1. [Steps to follow](#vs-code-steps)
   2. [Settings.json](#vs-code-json)

## VS Code Global Level User Setting [setting.json] <a name="vs-code"></a>

![VSCode](https://camo.githubusercontent.com/e81d11aac85343150bfcbb0f851f83ca3e8a1ba68b4cf8caaab304cb52c8cc4c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f56697375616c5f53747564696f5f436f64652d3030374143433f7374796c653d666f722d7468652d6261646765266c6f676f3d76697375616c25323073747564696f253230636f6465266c6f676f436f6c6f723d7768697465)

###

### Steps to follow <a name="vs-code-steps"></a>

1. Open VS Code.

2. Go to Settings Or, press `Ctrl + ,`.

3. Click on the 3rd Icon from Top Right Side, named: `Open Settings (JSON)`.

4. Copy-Paste the below settings.json.

5. Font Installation: `FIRA CODE` (needs to installed to use).

   ```bash
   sudo dnf install fira-code-fonts
   ```

### Settings.json <a name="vs-code-json"></a>

```json
{
  // editor
  "editor.fontSize": 16,
  "editor.fontFamily": "Fira Code, Consolas, Courier New, monospace",
  "editor.fontLigatures": true,
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "editor.suggestSelection": "first",
  "editor.guides.bracketPairs": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.quickSuggestions": {
    "strings": true
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "foreground": "#999999",
          "fontStyle": "italic"
        }
      }
    ]
  },
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 500,

  // cursor
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",

  //terminal
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.fontFamily": "Fira Code, Consolas, Courier New, monospace",

  // workbench customization
  "workbench.colorTheme": "Omni",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorCustomizations": {
    "editorCursor.foreground": "#ffff00",
    "terminal.background": "#1A1824",
    "terminal.foreground": "#DEE0F4",
    "terminalCursor.background": "#1A1824",
    "terminalCursor.foreground": "#D9D8EF",
    "terminal.ansiBlack": "#171421",
    "terminal.ansiBlue": "#12488B",
    "terminal.ansiBrightBlack": "#171421",
    "terminal.ansiBrightBlue": "#2AA1B3",
    "terminal.ansiBrightCyan": "#8BA59B",
    "terminal.ansiBrightGreen": "#26A269",
    "terminal.ansiBrightMagenta": "#A347BA",
    "terminal.ansiBrightRed": "#FB543F",
    "terminal.ansiBrightWhite": "#D0CFCC",
    "terminal.ansiBrightYellow": "#A2734C",
    "terminal.ansiCyan": "#2AA1B3",
    "terminal.ansiGreen": "#26A269",
    "terminal.ansiMagenta": "#A347BA",
    "terminal.ansiRed": "#FB543F",
    "terminal.ansiWhite": "#D0CFCC",
    "terminal.ansiYellow": "#A2734C"
  },

  //  Debug Console
  "debug.console.fontSize": 16,

  // Code Runner [Extension Settings]
  "code-runner.runInTerminal": true,
  "code-runner.saveFileBeforeRun": true,
  "code-runner.clearPreviousOutput": true,

  // Live Server [Extension Settings]
  "liveServer.settings.root": "/",
  "liveServer.settings.donotShowInfoMsg": true,

  // Snipped (Screenshot) [Extension Settings]
  "snipped.enablePng": true,

  // Better Comments [Extension Settings]
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00", // !Red
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#3498DB", // ?Blue
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#ffffff", // //White
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#FF8C00", // todo Orange
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#FFD700", // *Golden
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },

    {
      "tag": "^",
      "color": "#FF1493", // ^Pink
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],

  // Code Spell Checker [Extension Settings]
  "cSpell.userWords": [
    "ALLARR",
    "Aritra",
    "Arsh",
    "autoboxing",
    "binpow",
    "Brijmohan",
    "cerr",
    "Choudhary",
    "CHOUDHURY",
    "chrono",
    "Cinetro",
    "classpath",
    "Cloneable",
    "Consolas",
    "cout",
    "cpptools",
    "donot",
    "endl",
    "esbenp",
    "factorypath",
    "Filmingg",
    "Filmistry",
    "Fira",
    "Flowbite",
    "FMCG",
    "fontkit",
    "FORC",
    "FORN",
    "FORSQ",
    "freopen",
    "Gaurav",
    "Glassmorphism",
    "GYMYAM",
    "harshad",
    "imax",
    "imdb",
    "imin",
    "INFF",
    "Intellicode",
    "isit",
    "istream",
    "krishnamurthy",
    "llmax",
    "llmin",
    "LLONG",
    "loopc",
    "loopn",
    "lsum",
    "maxl",
    "maxll",
    "maxv",
    "memset",
    "minll",
    "minv",
    "Mohan",
    "ondataavailable",
    "ostream",
    "Playfair",
    "Quokka",
    "REVERSEARR",
    "revloop",
    "RFOR",
    "rloop",
    "rsum",
    "Screno",
    "Screnoo",
    "semibold",
    "SORTARR",
    "stdc",
    "Subarray",
    "swal",
    "sweetalert",
    "tailwindcss",
    "TANMOY",
    "tribonacci",
    "tsum",
    "vect",
    "Vikrant",
    "VPII",
    "vpll",
    "vsintellicode",
    "xorr",
    "xtra"
  ],

  // Tailwind CSS
  "tailwindCSS.emmetCompletions": true,
  "tailwindCSS.includeLanguages": {
    "html": "html",
    "javascript": "javascript",
    "css": "css"
  },

  "C_Cpp.files.exclude": {
    "**/.vscode": true,
    "**/.vs": true
  },

  // Error Lens
  "errorLens.followCursor": "allLines",

  // Code Formatting
  "editor.detectIndentation": false,
  "editor.tabSize": 2,
  "prettier.proseWrap": "always",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "[c]": {
    "editor.defaultFormatter": "xaver.clang-format"
  },
  "[objective-c]": {
    "editor.defaultFormatter": "xaver.clang-format"
  },
  "[cpp]": {
    "editor.wordBasedSuggestions": "off",
    "editor.suggest.insertMode": "replace",
    "editor.semanticHighlighting.enabled": true,
    "editor.defaultFormatter": "xaver.clang-format"
  },
  "[java]": {
    "editor.defaultFormatter": "xaver.clang-format"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "always",
    "source.fixAll.tslint": "always",
    "source.organizeImports": "always"
  },
  "eslint.alwaysShowStatus": true,
  "css.lint.unknownAtRules": "ignore",

  // C++ Intellisense [Extension Settings]
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "C_Cpp.default.intelliSenseMode": "linux-gcc-x64",

  // File Exclusion
  "files.exclude": {
    "**/.classpath": true,
    "**/.factorypath": true,
    "**/.git": false,
    "**/.project": true,
    "**/.settings": true
  }
}
```
