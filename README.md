# MDX Editor for Obsidian

Edit `.mdx` files in Obsidian with visual and source modes.

## Install

Download `manifest.json`, `main.js`, and `styles.css` from the latest release. Place them in `<vault>/.obsidian/plugins/mdx-editor`, then enable **MDX Editor** under **Settings → Community plugins**.

You can also install `arjunkmrm/mdx-editor` with [BRAT](https://github.com/TfTHacker/obsidian42-brat).

## Development

Install dependencies and build the plugin:

```bash
bun install
bun run build
```

Copy `manifest.json`, `main.js`, and `styles.css` into `<vault>/.obsidian/plugins/mdx-editor`. Run `bun run dev` while developing and reload Obsidian after each build.

## License

MIT
