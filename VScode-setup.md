# VS code setup
Sharing my theme color, extensions and settings for **Visual Studio Code Editor**.

# Theme 
I use the [One Monokai Theme](https://marketplace.visualstudio.com/items?itemName=azemoh.one-monokai) with a **little** of my style :) **"Check my** `settings.json` **file"** at `workbench.colorCustomizations` and `editor.tokenColorCustomizations`

# Extensions
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) to automatically close HTML tags. 
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) to automatically update matching HTML tags.
* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) to highlight colors in the code.
* [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) analyzes your Java Script code to quickly find problems.
* [Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) display an image preview next to the code.
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) new file and folder icons.
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) to automatically format code.
* [TODO highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) to highlight annotations within your code **"Check my** `settings.json` **file"** at `TODO Higlight`.

# Settings
`Auto Save` set to `onFocusChange`, to automatically save files.

`Default Formatter` set to `Prettier - Code formatter (esbenp.prettier-vscode)`, to enable the Prettier extension to format our code.

`Format on Save` set to `true`, to have Prettier format our code each time we save it.

`Word Wrap` set to `on`, to avoid vertical scrollbars for long content.

`Tab Size` set to `2`, for better code readability.

`Bracket Pair` Colorization set to `Enabled`, to get colorized brackets **"Check my** `settings.json` **file"** at `editorBracketHighlight (Parantezele)`.


# Theme colors + other settings 
**Please be free to change colors according to your style if you didn't like mine**

My `settings.json` file:

```
{
"settingsSync.ignoredExtensions": ["ms-ceintl.vscode-language-pack-ru"],
  
  "files.autoSave": "onFocusChange",
  
  "editor.fontSize": 18,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.wordWrap": "on",
  "editor.formatOnSave": true,
  "editor.fontFamily": "Menlo",
  "editor.defaultFormatter": "esbenp.prettier-vscode",

// TODO Higlight
  "todohighlight.isCaseSensitive": true,
  "todohighlight.keywords": [
    {
      "text": "VIDEO",
      "color": "#333",
      "backgroundColor": "#3498db"
    },
    
    {
      "text": "FIXME",
      "color": "#333",
      "backgroundColor": "#e67e22"
    },
    
    {
      "text": "LEX",
      "color": "#333",
      "backgroundColor": "#f1c40f"
    },
    
    {
      "text": "BUG",
      "color": "#333",
      "backgroundColor": "#e74c3c"
    },
    
    {
      "text": "TODO",
      "color": "#333",
      "backgroundColor": "#2ecc71"
    }
  ],
  
  "terminal.integrated.fontFamily": "Courier",
  
  "terminal.integrated.fontSize": 16,
  
  "workbench.iconTheme": "material-icon-theme",
  
  "eslint.run": "onSave",
  
  "editor.tabSize": 2,
  
  "workbench.colorCustomizations": {
  
    // Parantezele ( (), {}, [] )
    "editorBracketHighlight.foreground1": "#fe8300",
    "editorBracketHighlight.foreground2": "#fba0e9",
    "editorBracketHighlight.foreground3": "#e4ee73",
    "editorBracketHighlight.foreground4": "#39f869",
    "editorBracketHighlight.foreground5": "#b246e0",
    "editorBracketHighlight.foreground6": "#ebeaea",
    "editorBracketHighlight.unexpectedBracket.foreground": "#ff5555",

    // Culoarea la linie verticala
    "editorIndentGuide.background1": "#5f6c7dba",

    // Main color
    "editor.background": "#27262a",

    // Culoarea la , <>, H1, /
    "editor.foreground": "#ffffff",

    // Culoarea la tab sub search
    "editorGroupHeader.tabsBackground": "#211f22",

    // Culoarea la line number
    "editorLineNumber.foreground": "#6980ac",
    "editorLineNumber.activeForeground": "#d40303",

    // Culoarea la tab unde este scris line number
    "editorGutter.background": "#27262a",

    // Culoarea la selectie a textului
    "editor.selectionBackground": "#6980ac4a",

    // Culoarea la search word tab ( ctrl + F )
    "editorWidget.background": "#353e4d",
    "editorWidget.foreground": "#ff0000",
    "editorWidget.border": "#211f22",

    // Culoarea la slider
    "scrollbarSlider.background": "#ff040476",
    "scrollbarSlider.activeBackground": "#6980ac4a",
    "scrollbarSlider.hoverBackground": "#6980ac4a",

    // Culoarea la sidebar extrem din stinga ( icons )
    "activityBar.background": "#211f22",
    "activityBar.foreground": "#ff0000",
    "activityBar.inactiveForeground": "#c6c6c6",

    // Culoarea la sidebar cind apesi icon ( folders )
    "sideBar.background": "#211f22",
    "sideBarTitle.foreground": "#ff0000",
    "sideBarSectionHeader.foreground": "#d50101",
    "sideBarSectionHeader.background": "#211f22",

    // Culoarea la border cind ii deschid sidebar
    "focusBorder": "#6980ac7d",

    // Culoarea la butoane
    "button.background": "#c00202",

    // Culoarea la taburi deasupra la editor ( App.js, index.js, index.html )
    "tab.inactiveBackground": "#211f22",
    "tab.activeBackground": "#353e4d",

    // Culoarea la notificare Changes ( ctrl + Shift + G)
    "badge.background": "#c00202",
    "badge.foreground": "#ffffff",

    // Culoarea la Bar de jos
    "statusBar.background": "#211f22",
    "statusBar.foreground": "#99a2b4",

    // Culoarea la titleBar ( tab de sus )
    "titleBar.activeBackground": "#211f22",
    "titleBar.inactiveBackground": "#211f22",
    "titleBar.activeForeground": "#6980ac",
    // "titleBar.border": "#6980ac",

    // Culoarea la Menu de la TitleBar
    "menubar.selectionForeground": "#ff0000",
    "menu.selectionBackground": "#3e4556",
    "menu.selectionForeground": "#ff0000",
    "menu.foreground": "#6980ac",
    "menu.background": "#211f22",
    "menu.border": "#6980ac"

  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "storage.type.function.js",
          "storage.type.js",
          "constant.language.boolean.false.js",
          "constant.language.boolean.true.js",
          "support.variable.property.js",
          "constant.language.null.js",
          "constant.language.undefined.js",
          "storage.type.function.arrow.js",
          "support.constant.property-value.css",
          "support.constant.font-name.css"
        ],
        "settings": {
          "foreground": "#78DCE8"
        }
      },
      {
        "scope": [
          "entity.name.tag.js",
          "keyword.control.flow.js",
          "keyword.control.conditional.js",
          "keyword.operator.assignment.js",
          "keyword.operator.comparison.js",
          "keyword.operator.ternary.js",
          "keyword.operator.spread.js",
          "keyword.operator.logical.js",
          "keyword.control.import.js",
          "keyword.control.export.js",
          "keyword.control.default.js",
          "keyword.control.from.js",
          "keyword.operator.arithmetic.js",
          "keyword.operator.relational.js",
          "entity.name.tag.html",
          "entity.name.tag.css",
          "entity.other.attribute-name.class.css",
          "keyword.control.at-rule.import.css",
          "keyword.other.unit.percentage.css",
          "keyword.other.unit.rem.css",
          "keyword.other.unit.vh.css",
          "keyword.other.unit.fr.css",
          "keyword.other.unit.px.css"
        ],
        "settings": {
          "foreground": "#f84773"
        }
      },
      {
        "scope": [
          "variable.other.constant.js",
          "support.class.component.js",
          "variable.other.object.js",
          "variable.other.object.property.js"
        ],
        "settings": {
          "foreground": "#639efc"
        }
      },
      {
        "scope": [
          "entity.name.function.js",
          "entity.other.attribute-name.js",
          "entity.other.attribute-name.html",
          "support.function.url.css",
          "support.function.misc.css",
          "entity.other.attribute-name.css",
          "support.function.transform.css"
        ],
        "settings": {
          "foreground": "#9fcf6f"
        }
      },
      {
        "scope": "variable.parameter.js",
        "settings": {
          "foreground": "#f88f5b"
        }
      },
      {
        "scope": ["constant.numeric.decimal.js", "constant.numeric.css"],
        "settings": {
          "foreground": "#AB9DF2"
        }
      }
    ]
  },

  "workbench.colorTheme": "One Monokai"
}
```

