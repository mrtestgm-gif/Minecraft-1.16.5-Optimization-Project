# Clever Minecraft 1.16.5 launcher

This branch contains a simple Netlify-ready launcher with Direct, about:blank, and blob: options.

- `index.html`: launcher with Clever tab title and icon.
- `game.html`: exact GitHub blob from Codex's verified recovery (no runtime modifications).
- `clever-favicon.svg`: self-hosted blue C icon fallback.

SHA-256 of `game.html` (recorded by Codex):
`e3e0d7400fade55afe792b393e090ebfb18521aec0066af283a28799e634f714`

Download this branch as ZIP, extract it, and deploy the folder to Netlify. Or connect this branch as your Netlify deployment source.

The about:blank and blob: methods use a fullscreen iframe loading the same website and do not bypass school or network restrictions. Some browsers can override the tab title/icon or block iframe game behavior; Direct launch is provided as a fallback.
