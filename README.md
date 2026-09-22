# 🇸🇦 Saudi National Day VS Code Theme

Celebrate Saudi National Day with a custom green VS Code theme featuring a Saudi flag background and an anime sticker.

## Installation

1. Install the Custom CSS and JS Loader extension in VS Code.
2. Download the `sticker.css` file from this repository.
3. Open VS Code Settings (JSON).
4. Add the following setting, replacing the path with the location of your downloaded CSS file:

```json
"vscode_custom_css.imports": [
  "file:///YOUR/PATH/TO/sticker.css"
]
```

5. Open the Command Palette and run `Enable Custom CSS and JS`.
6. Restart VS Code when prompted.

**Note:** VS Code may display a warning about a corrupted installation after enabling custom CSS. This is an expected warning associated with the extension.

## Included Files

- `sticker.css` — Custom theme styling.
- `saudi_flag.png` — Saudi flag background.
- `anime.png` — Anime sticker.

## License

MIT License.
