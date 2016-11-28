# Config store for local environment

## Visual Studio Code

[Official website][VSC]    
[VSC features post][VSC-features]

### User settings config
Select **File** > **Preferences** > **User Settings** (or press **Ctrl+Shift+P**, type `user` and press **Enter**) to edit the user `settings.json` file.

`settings.json`:
```sh
{
    "locale": "en",
    "editor.wordWrap": true,
    "editor.renderWhitespace": true,
    "editor.fontFamily": "Droid Sans Mono",
    "editor.lineHeight": 22px,
    "editor.fontSize": 15
}
```

### User keybinding config
**Ctrl+Shift+P** > type `Keybinding` > press **Enter**
`keybindings.json`:
```sh
[
    { "key": "ctrl+q",               "command": "editor.action.commentLine",
                                     "when": "editorTextFocus && !editorReadonly" },
    { "key": "ctrl+/",               "command": "",
                                     "when": "editorTextFocus && !editorReadonly" },
]
```

### Color Theme
**Ctrl+Shift+P** > type `Color Theme` > select `Monokai`

### Terminal
**Ctrl+Shift+P** > type `Terminal` and you will see all features available

### File Icon Theme
**Ctrl+Shift+P** > type `Terminal` > choose `Seti`
or
**Ctrl+P** > type `ext install vscode-icons` > install **vscode-icons** extension

## Extensions:

### Git Easy
**Ctrl+P** > type `ext install git-easy`
###  AutoFileName
**Ctrl+P** > type `ext install autofilename`
### ESLint
**Ctrl+P** > type `ext install vscode-eslint`
### JavaScript (ES6) Code Snippets
**Ctrl+P** > type `ext install JavaScriptSnippets`
### Project Manager
**Ctrl+P** > type `ext install project-manager`
### Git History
**Ctrl+P** > type `ext install githistory`
### Align 
**Ctrl+P** > type `ext install Align`
Press `[ctrl+alt+a]`




[VSC]: https://code.visualstudio.com/b?utm_expid=101350005-35.Eg8306GUR6SersZwpBjURQ.1&utm_referrer=https%3A%2F%2Fwww.google.by%2F
[VSC-features]: https://scotch.io/tutorials/best-of-visual-studio-code-features-plugins-acting-like-atom-and-sublime
