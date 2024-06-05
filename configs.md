<h1>Configurações</h1>

<p>Para utilizar, coloque estas configurações dentro do arquivo settings.json, que pode ser acessado da seguinte forma:</p>

```bash
Aperte CTRL + SHIFT + P para acessar a Paleta de Comandos
Busque por:

Preferências: Abrir as Configurações do Usuário (JSON)
Preferences: Open User Settings (JSON)

E cole o código abaixo:
```

```json
{
    "editor.wordWrap": "on",
    "files.autoSave": "afterDelay",
    "css.completion.completePropertyWithSemicolon": false,
    "git.decorations.enabled": false,
    "git.enabled": false,
    "workbench.startupEditor": "none",
    "editor.tabSize": 2,
    "workbench.colorTheme": "Default Dark+",
    "workbench.iconTheme": "vscode-icons",
    "sass.format.deleteWhitespace": false,
    "sass.format.deleteEmptyRows": false,
    "scss.completion.completePropertyWithSemicolon": false,
    "git.autoRepositoryDetection": false,
    "git.suggestSmartCommit": false,
    "explorer.compactFolders": false,
    "[prisma]": {
        "editor.formatOnSave": true
    },
    "window.menuBarVisibility": "toggle",
    "window.commandCenter": false,
    "workbench.layoutControl.enabled": false,
    "editor.fontSize": 14,
    "editor.lineHeight": 1.4,
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "editor.scrollbar.horizontal": "hidden",
    "editor.scrollbar.vertical": "hidden",
    "workbench.statusBar.visible": false,
    "apc.electron": {
        "titleBarStyle": "hidden"
    },
    "apc.header": {
        "height": 36
    },
    "apc.listRow": {
        "height": 24
    },
    "apc.stylesheet": {
        ".editor-actions": "display: none",
    },
    "terminal.integrated.fontSize": 14,
    "editor.stickyScroll.enabled": false,
    "breadcrumbs.enabled": false,
    "color-highlight.matchWords": true,
    "color-highlight.sass.includePaths": [

    ],
    "editor.wordWrapColumn": 130,
    "editor.minimap.maxColumn": 60,
    "prisma.showPrismaDataPlatformNotification": false,
    "files.associations": {
        "*.css": "tailwindcss"
    },
    "tailwindCSS.emmetCompletions": true,
    "workbench.activityBar.location": "hidden"
}
```