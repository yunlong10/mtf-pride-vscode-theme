<p align="center">
  <img src="banner.png" alt="MTF Pride Theme" width="100%" />
</p>

# MTF Pride Theme for VS Code

A beautiful light color theme for Visual Studio Code, inspired by the **transgender pride flag** — light blue, pink, and white.

## Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Background | ![#FAFAFF](https://via.placeholder.com/12/FAFAFF/FAFAFF.png) | `#FAFAFF` |
| Foreground | ![#3B3252](https://via.placeholder.com/12/3B3252/3B3252.png) | `#3B3252` |
| Blue (functions) | ![#1A8FB5](https://via.placeholder.com/12/1A8FB5/1A8FB5.png) | `#1A8FB5` |
| Pink (keywords) | ![#D1568C](https://via.placeholder.com/12/D1568C/D1568C.png) | `#D1568C` |
| Lavender (types) | ![#7C4DBA](https://via.placeholder.com/12/7C4DBA/7C4DBA.png) | `#7C4DBA` |
| Rose (strings) | ![#9E5580](https://via.placeholder.com/12/9E5580/9E5580.png) | `#9E5580` |
| Amber (constants) | ![#C47A20](https://via.placeholder.com/12/C47A20/C47A20.png) | `#C47A20` |
| Steel (operators) | ![#4A80B0](https://via.placeholder.com/12/4A80B0/4A80B0.png) | `#4A80B0` |

## Installation

### From Marketplace

1. Open **Extensions** sidebar in VS Code (`Ctrl+Shift+X`)
2. Search for `MTF Pride`
3. Click **Install**
4. Go to `Preferences: Color Theme` and select **MTF Pride**

### From VSIX

1. Download the `.vsix` file from [Releases](https://github.com/yunlong10/mtf-pride-vscode-theme/releases)
2. Run `code --install-extension mtf-pride-vscode-theme-x.x.x.vsix`

## Development

```bash
# Clone the repo
git clone https://github.com/yunlong10/mtf-pride-vscode-theme.git
cd mtf-pride-vscode-theme

# Open in VS Code
code .

# Press F5 to launch Extension Development Host and preview the theme
```

## Publishing

```bash
# Install vsce
npm install -g @vscode/vsce

# Package
vsce package

# Publish
vsce publish
```

## License

[MIT](LICENSE)
