# Sepia Summit for Discord

A translucent sepia Discord theme made to match the [Sepia Summit](https://github.com/NexusKiwi/Sepia-Summit) KDE Plasma desktop. Your wallpaper, audio visualiser and desktop widgets stay visible behind floating, rounded panels.

## Install (Vencord)

1. Open **Vencord Settings** and turn on **Enable window transparency**, then restart Discord.
2. Open **Themes → Online Themes** and paste this link:

   ```
   https://nexuskiwi.github.io/Sepia-Summit-Discord/sepia-summit.theme.css
   ```

The theme updates from this repo whenever Discord reloads it.

Without window transparency the theme still works, but you won't see your desktop behind it.

## Fonts

The theme uses the same fonts as the Sepia Summit stats panel: **Noto Sans Mono**, **Noto Serif** and **Noto Sans**. They need to be installed on your system. Custom username fonts from Discord still show as normal.

## Customising

Copy the theme into Vencord's QuickCSS and change the values at the top:

| setting | default | what it does |
|---|---|---|
| `--sepia-alpha-window` | `0.4` | tint behind the whole window |
| `--sepia-alpha-panel` | `0.5` | server list, channels and members |
| `--sepia-alpha-chat` | `0.28` | chat background |
| `--sepia-alpha-card` | `0.32` | message groups and message box |
| `--sepia-gap` | `10px` | space between panels |
| `--sepia-radius` | `12px` | corner rounding |

Lower alpha values are more see-through.

Discord changes its interface often, so parts of the layout may need updating after a Discord release.

## Credits

The floating panel and message card layout is adapted from [Discord+](https://github.com/PlusInsta/discord-plus) by Paulo Ødegård, under the MIT License.

## License

MIT. See [LICENSE](LICENSE), which includes the Discord+ notice.
