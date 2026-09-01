# MDX Editor for Obsidian

Edit `.mdx` files in Obsidian with a visual rich-text editor and an exact source mode.

## Features

- Registers `.mdx` as a native Obsidian file view.
- Supports headings, lists, quotes, tables, links, frontmatter, thematic breaks, and fenced code blocks.
- Preserves custom JSX components through a generic block editor.
- Provides source and diff modes for syntax the visual editor cannot represent directly.
- Follows Obsidian light and dark themes.
- Uses Obsidian's native file lifecycle, saving, and key handling.

## Manual installation

Download `manifest.json`, `main.js`, and `styles.css` from the latest release. Place them in `<vault>/.obsidian/plugins/mdx-editor`, then enable **MDX Editor** under **Settings → Community plugins**.

For beta installation, add `arjunkmrm/mdx-editor` through [BRAT](https://github.com/TfTHacker/obsidian42-brat).

## Development

Install dependencies and build the plugin:

```bash
bun install
bun run build
```

Copy `manifest.json`, `main.js`, and `styles.css` into `<vault>/.obsidian/plugins/mdx-editor`. Run `bun run dev` while developing and reload Obsidian after each build.

## Releases

Release tags match the version in `manifest.json` exactly and do not use a `v` prefix. Each GitHub release includes `manifest.json`, `main.js`, and `styles.css`.

## License

MIT
