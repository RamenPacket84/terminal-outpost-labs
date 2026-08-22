## Terminal Outpost Labs

Dark, minimalist Omarchy theme.

## Installation

Run command:
omarchy theme install https://github.com/RamenPacket84/terminal-outpost-labs.git

## Fastfetch

The optional Fastfetch configuration includes a custom Terminal Outpost Labs
terminal-art logo and matching colors.

From the root of this repository, back up any existing Fastfetch configuration
and install the included files:

```bash
mkdir -p ~/.config/fastfetch

if [ -f ~/.config/fastfetch/config.jsonc ]; then
  cp ~/.config/fastfetch/config.jsonc ~/.config/fastfetch/config.jsonc.backup
fi

cp fastfetch/terminal-outpost-labs.txt ~/.config/fastfetch/
cp fastfetch/config.jsonc ~/.config/fastfetch/config.jsonc
```

Preview the result:

```bash
fastfetch
```

The included `config.jsonc` replaces your current Fastfetch layout. To restore
your previous configuration:

```bash
mv ~/.config/fastfetch/config.jsonc.backup ~/.config/fastfetch/config.jsonc
```

## Wallpapers

Includes four wallpapers featuring alpine, wooded, stream, and desert outposts.
