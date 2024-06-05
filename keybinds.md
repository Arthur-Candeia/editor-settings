<h1>Atalhos de Teclado</h1>

<p>Para utilizar, coloque estas configurações dentro do arquivo keybindings.json, que pode ser acessado da seguinte forma:</p>

```bash
Aperte CTRL + SHIFT + P para acessar a Paleta de Comandos
Busque por:

Preferências: Abrir Atalhos de Teclado (JSON)
Preferences: Open Keyboard Shortcuts (JSON)

E cole o código abaixo:
```

```json
[
  {
    "key": "ctrl+m",
    "command": "explorer.newFile"
  },
  {
    "key": "ctrl+n",
    "command": "explorer.newFolder"
  },
  {
    "key": "ctrl+q",
    "command": "workbench.files.action.focusFilesExplorer",
  },
  {
    "key": "ctrl+shift+q",
    "command": "workbench.action.focusActiveEditorGroup"
  },
  {
    "key": "ctrl+alt+p",
    "command": "workbench.files.action.collapseExplorerFolders",
  },
  {
    "key": "ctrl+k ctrl+a",
    "command": "editor.toggleFold",
    "when": "editorTextFocus && foldingEnabled"
  },
  {
    "key": "ctrl+k ctrl+l",
    "command": "editor.action.deleteLines",
    "when": "textInputFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+d",
    "command": "editor.action.addSelectionToPreviousFindMatch"
  },
  {
    "key": "ctrl+alt+oem_period",
    "command": "workbench.action.focusActivityBar"
  },
  {
    "key": "ctrl+alt+oem_comma",
    "command": "workbench.action.activityBarLocation.hide"
  },
  {
    "key": "shift+alt+pagedown",
    "command": "editor.action.smartSelect.shrink",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+alt+left",
    "command": "-editor.action.smartSelect.shrink",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+alt+pageup",
    "command": "editor.action.smartSelect.expand",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+alt+right",
    "command": "-editor.action.smartSelect.expand",
    "when": "editorTextFocus"
  },
  {
    "key": "shift+alt+down",
    "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+down",
    "command": "-editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "shift+alt+up",
    "command": "editor.action.copyLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+up",
    "command": "-editor.action.copyLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  }
]
```