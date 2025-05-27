# starter-pack
When I move computers, here's what I need to do (Macbook)

- [ ] Install [brew](https://brew.sh/)
- [ ] Add brew to path (for m1 chips)
`echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile`
`eval "$(/opt/hebrew/bin/brew shellenv)"`
- [ ] Install [NVM](https://github.com/nvm-sh/nvm)
- [ ] Install [Oh my zsh](https://ohmyz.sh/#install)
- [ ] Install [iTerm](https://iterm2.com/)
- [ ] Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [ ] [Setup verified commits](https://docs.github.com/en/authentication/managing-commit-signature-verification)
- [ ] Install [VSCode](https://code.visualstudio.com/)
- [ ] Install [RayCast](https://www.raycast.com/)

## Visual Studio Code
### Theme
- SynthWave '84
- Font is [Fira Code iScript](https://github.com/kencrocken/FiraCodeiScript)


### Extensions
- GitLens
- Tailwind CSS Intellisense
- Alphabetical Sorter
- Background
- BongoCat
- Bracket Pair Color DLW
- Escape HTML Code
- ESLint
- Github Actions
- GraphQL
- Hotline Icons
- Indent Rainbow
- Increment Selection
- Prettier
- SVG Preview
- TODO Tree
- TS Import Sorter
### User Settings
```json
{
  "workbench.startupEditor": "newUntitledFile",
  "editor.tabSize": 2,
  "files.trimTrailingWhitespace": true,
  "editor.renderWhitespace": "boundary",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.formatOnSaveTimeout": 750,
  "files.trimFinalNewlines": false,
  "javascript.preferences.quoteStyle": "single",
  "typescript.preferences.quoteStyle": "single",
  "vetur.completion.autoImport": true,
  "vetur.validation.template": false,
  "vetur.format.defaultFormatterOptions": {
    "prettier": {
      "singleQuote": true
    }
  },
  "editor.mouseWheelZoom": false,
  "editor.fontSize": 18,
  "terminal.integrated.fontSize": 18,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "prettier.jsxSingleQuote": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "prettier.disableLanguages": ["html"],
  "todo-tree.tree.showScanModeButton": false,
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "debug.console.closeOnEnd": true,
  "typescript.format.semicolons": "insert",
  "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
  "javascript.suggest.completeFunctionCalls": true,
  "terminal.integrated.shell.osx": "/bin/zsh",
  // eslint
  "eslint.probe": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "vue",
    "markdown"
  ],
  "eslint.options": {},
  "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact"],
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "michelemelluso.code-beautifier"
  },
  "angular.experimental-ivy": true,
  "diffEditor.codeLens": true,
  "editor.accessibilitySupport": "off",
  "git.confirmSync": false,
  "todo-tree.general.tags": ["BUG", "HACK", "FIXME", "TODO", "XXX", "[ ]", "[x]"],
  "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
  "workbench.editorAssociations": {
    "*.md": "vscode.markdown.preview.editor"
  },
  "gitlens.advanced.messages": {
    "suppressCreatePullRequestPrompt": true
  },
  "gitlens.gitCommands.skipConfirmations": [
    "fetch:command",
    "stash-push:command",
    "switch:command",
    "push:command"
  ],
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "terminal.integrated.shellArgs.windows": ["--login"],
  "terminal.integrated.profiles.windows": {
    "Git Bash": {
      "path": "C:\\Program Files\\Git\\bin\\bash.exe",
      "args": ["--login"]
    }
  },
  "editor.minimap.enabled": false,
  "security.workspace.trust.untrustedFiles": "open",
  "editor.tabCompletion": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "workbench.colorTheme": "SynthWave '84",
  "git.autofetch": true,
  "[scss]": {
    "editor.defaultFormatter": "michelemelluso.code-beautifier"
  },
  "npm.keybindingsChangedWarningShown": true,
  "[javascriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "eslint.autoFixOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "terminal.integrated.scrollback": 1000000,
  "terminal.integrated.persistentSessionScrollback": 1000000,
  "git.ignoreRebaseWarning": true,
  "editor.fontFamily": "'Fira Code iScript', 'Operator Mono', 'Roboto Mono', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontWeight": 400,
  "glassit-linux.opacity": 10,
  "glassit.alpha": 255,
  "prettier.requireConfig": true,
  "prettier.printWidth": 100,
  "editor.quickSuggestions": {
    "strings": true
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "typescript.preferences.importModuleSpecifier": "non-relative",
  "workbench.editor.labelFormat": "medium",
  "importSorter.importStringConfiguration.tabSize": 2,
  "importSorter.sortConfiguration.customOrderingRules.rules": [
    {
      "type": "importMember",
      "regex": "^$",
      "orderLevel": 5,
      "disableSort": true
    },
    {
      "regex": "^[^.@]",
      "orderLevel": 10
    },
    {
      "regex": "^[@]",
      "orderLevel": 15
    },
    {
      "regex": "^[.]",
      "orderLevel": 30
    }
  ],
  "php.validate.executablePath": "/usr/local/etc/php/8.3/",
  "liveServer.settings.donotVerifyTags": true,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "html.completion.attributeDefaultValue": "singlequotes",
  "prettier.singleQuote": true,
  "workbench.settings.applyToAllProfiles": ["prettier.singleQuote"],
  "prettier.useEditorConfig": false,
  "editor.formatOnType": true,
  "prettier.configPath": ".prettierrc",
  "editor.formatOnSave": true,
  "terminal.integrated.fontWeightBold": "bold",

  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          //following will be in italic (=FlottFlott)
          "comment",
          "entity.name.type.class", //class names

          "keyword", //import, export, return…
          "constant", //String, Number, Boolean…, this, super
          "storage.modifier", //static keyword
          "storage.type.class.js", //class keyword
          "entity.name.method.js",
          "entity.name.class.js",
          "entity.name.tag.doctype",
          "entity.other.attribute-name",
          "entity.other.attribute-name.tag.jade",
          "entity.other.attribute-name.tag.pug"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "scope": [
          //following will be excluded from italics (VSCode has some defaults for italics)
          "invalid",
          "keyword.operator",
          "constant.numeric.css",
          "keyword.other.unit.px.css",
          "constant.numeric.decimal.js",
          "constant.numeric.json"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },

  "background.fullscreen": {
    "images": ["file:///Users/elilemons/Documents/Dev/backgrounds/wp4041942-outrun-wallpapers.jpg"],
    "opacity": 0.95,
    "size": "cover",
    "position": "center",
    "interval": 0
  },
  "workbench.iconTheme": "sweet-vscode-icons",
  "workbench.productIconTheme": "bongocat",
  "terminal.integrated.fontFamily": "'Fira Code iScript', 'Operator Mono', 'Roboto Mono', Menlo, Monaco, 'Courier New', monospace",
  "terminal.integrated.fontWeight": "normal"
}

```
