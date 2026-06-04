# ghostty

[Ghostty](https://ghostty.org) is a terminal emulator written by [Mitchell Hashimoto](https://github.com/mitchellh).

## Usage

Electron Highlighter is included as a theme in Ghostty. To use it, add this line to your config file (likely `~/.config/ghostty/config`): 

```
theme = electron-highlighter
```

Alternatively, you can copy the individual properties from the `config` file and modify them if you would like.

Enjoy! :heart:

## Electron Highlighter Day (light)

A light variant is available alongside the dark theme. Use the `electron-highlighter-day` file in this
folder the same way you use the dark one. The Day files are generated from the `palette/` repo —
edit the palette there and run `npm run build` to regenerate.
