## Requirements
- You need to install the JetBrains Mono font in order to apply it correctly in VS Code
link for install: https://www.jetbrains.com/pt-br/lp/mono/

- You need to isntall this extension for Vscode

 VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension
```bash Name: Apc Customize UI++
Id: drcika.apc-extension
Description: Advanced VSCode user interface customizations. Very experimental.
Version: 0.3.6
Publisher: drcika
```
---

## 🛠️ VS Code Configuration Guide
- Open Visual Studio Code.

1. Press Ctrl + Shift + P (or Cmd + Shift + P on macOS) to open the Command Palette.

2. Search for and select:
```bash Preferences: Open Settings (JSON)```

3. Paste the configuration file "vscodesettings.json" configuration into the file

---

## 🧠 What Each Setting Does

| Setting                                        | Description                                                              |
| ---------------------------------------------- | ------------------------------------------------------------------------ |
| `"workbench.iconTheme"`                        | Sets the icon theme used in the sidebar (Change as you wanted).         |
| `"[jsonc]"`                                    | Defines default formatter for JSON with comments.                        |
| `"liveServer.settings.donotShowInfoMsg"`       | Suppresses the info message when using Live Server.                      |
| `"editor.fontSize"`                            | Sets the editor font size to 14px.                                       |
| `"files.autoSave"`                             | Automatically saves files after a short delay.                           |
| `"workbench.colorTheme"`                       | Applies the “Min Dark” color theme.                                      |
| `"editor.fontFamily"`                          | Uses “JetBrains Mono” font for better readability.                       |
| `"editor.lineHeight"`                          | Sets the spacing between lines to 1.8 for better legibility.             |
| `"editor.rulers"`                              | Adds vertical rulers at 80 and 120 characters to guide code line length. |
| `"editor.renderLineHighlight"`                 | Highlights the current line in the gutter.                               |
| `"editor.fontLigatures"`                       | Enables ligatures for advanced font styling.                             |
| `"explorer.compactFolders"`                    | Expands folder view instead of compacting them.                          |
| `"editor.semanticHighlighting.enabled"`        | Disables semantic highlighting.                                          |
| `"breadcrumbs.enabled"`                        | Turns off the breadcrumbs navigation feature.                            |
| `"terminal.integrated.fontSize"`               | Sets terminal font size to 14px.                                         |
| `"terminal.integrated.fontFamily"`             | Uses a Nerd Font for better terminal icons.                              |
| `"editor.scrollbar.vertical"` / `"horizontal"` | Hides scrollbars in the editor.                                          |
| `"workbench.layoutControl.enabled"`            | Disables layout switching UI.                                            |
| `"apc.listRow.height"`                         | Custom setting (likely for an extension) to define row height.           |
| `"apc.stylesheet"`                             | Custom CSS (extension-specific) to style parts of the UI.                |
| `"editor.cursorBlinking"`                      | Sets blinking animation of the cursor to “expand.”                       |
| `"editor.cursorSmoothCaretAnimation"`          | Enables smooth cursor movement animation.                                |
| `"emmet.includeLanguages"`                     | Enables Emmet abbreviations in JavaScript files as if they were JSX.     |
