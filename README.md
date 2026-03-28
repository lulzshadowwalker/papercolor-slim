# PaperColor Slim Theme (VS Code)

A minimal port of the PaperColor Slim colorscheme to Visual Studio Code.

This theme keeps the original goal intact: consistent colors, predictable highlighting, and no unnecessary complexity. It aims to stay out of your way and let you focus on the code.

## What this is

* A straightforward port of PaperColor Slim
* Designed for readability across different languages
* No heavy styling or visual noise
* Easy to override if you want to tweak things

## Themes included

* PaperColor Slim Dark

## Installation

1. Open Extensions in VS Code
2. Search for "PaperColor Slim Theme"
3. Install and select it from:
   Preferences → Color Theme

## Customization

You can override anything using VS Code’s built-in settings.

Example:

```json
"workbench.colorCustomizations": {
  "editor.background": "#1c1c1c"
},
"editor.tokenColorCustomizations": {
  "comments": "#6a737d"
}
```

## Notes

This is a port, not a one-to-one copy. Some differences are expected due to how VS Code handles syntax highlighting compared to Neovim.

The goal is to stay as close as possible to the original intent while working well within VS Code’s theming system.

## Credits

Based on the original PaperColor Slim project:
https://github.com/pappasam/papercolor-theme-slim

All credit for the design and philosophy goes to the original authors.

## Feedback

If something looks off or inconsistent, feel free to open an issue or suggest improvements.
