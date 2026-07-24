# Uwu Kawaii Pink for Nimbalyst

> A warm pastel theme for people who take their pink seriously.

**Uwu Kawaii Pink** is a light Nimbalyst theme built around soft rose, lilac,
cream, and mint surfaces. Dark mauve typography and saturated pink focus
states keep the editor comfortable for long sessions.

## Features

- Native Nimbalyst filesystem theme bundle — no extension, agent, or plugin required.
- Complete palette for editor surfaces, text, borders, states, and semantic colors.
- Small, inspectable install footprint: one `theme.json` file.
- Designed and verified on Nimbalyst for macOS.

## Install (macOS)

1. Download or clone this repository.

   ```bash
   git clone https://github.com/firekern/uwu-kawaii-pink.git
   cd uwu-kawaii-pink
   ```

2. Copy the theme bundle to Nimbalyst's local themes directory.

   ```bash
   DEST="$HOME/Library/Application Support/@nimbalyst/electron/themes"
   mkdir -p "$DEST"
   cp -R uwu-kawaii-pink "$DEST/"
   ```

3. Restart Nimbalyst. In **Settings → Themes**, choose **Uwu Kawaii Pink**
   from *Installed Themes* and click **Apply**.

## Update

```bash
cd uwu-kawaii-pink
git pull

DEST="$HOME/Library/Application Support/@nimbalyst/electron/themes"
rm -rf "$DEST/uwu-kawaii-pink"
cp -R uwu-kawaii-pink "$DEST/"
```

Restart Nimbalyst after updating.

## Uninstall

```bash
rm -rf "$HOME/Library/Application Support/@nimbalyst/electron/themes/uwu-kawaii-pink"
```

Restart Nimbalyst, then apply another theme from **Settings → Themes**.

## Repository layout

```text
.
├── uwu-kawaii-pink/
│   └── theme.json        # Theme bundle copied into Nimbalyst
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Contributing

Theme contributions are welcome. Keep changes limited to the Nimbalyst
filesystem theme schema and update `CHANGELOG.md` for visible changes.

## License

Released under the [MIT License](LICENSE).
