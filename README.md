<h3 align="center">
  MountNugget for <a href="https://github.com/sharkdp/bat">Bat</a>

  <img src="https://imgur.com/bQY71Ms.png" title="Tmux mountnugget colorscheme" style="width: 100%; max-width: 600px; text-align: center;"/>
</h3>

## Installation

1. Create a theme folder in bat's configuration directory:
   ```bash
   mkdir -p "$(bat --config-dir)/themes"
   ```
2. Download the theme (`MountNugget.tmTheme`) file to that directory.
3. Rebuild bat's cache:
   ```bash
   bat cache --build
   ```
4. Verify that the theme is installed by running `bat --list-themes`.

## Usage

Configure `bat` to use the MountNugget theme:

Edit your config file, located in `bat --config-file` (usually `~/.config/bat/config`), and add the following line:

```
--theme="MountNugget"
```

## Other themes

- [MountNugget.nvim](https://github.com/dlvandenberg/mountnugget.nvim)
- [MountNugget.terminal](https://github.com/dlvandenberg/mountnugget.terminal)

## Credits

This plugin is inspired by [Gruvbox](https://github.com/egel/tmux-gruvbox).

## License

[GPL-v3.0](LICENSE.txt)
