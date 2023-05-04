[light]:            https://user-images.githubusercontent.com/29710355/233753957-b581ff4c-bb70-4f13-8504-b3a4dd5c57e8.png
[dark]:             https://user-images.githubusercontent.com/29710355/233753967-87358b2b-aa49-4056-a5a4-891de58756df.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi
[ko-fi]:            https://ko-fi.com/saltssaumure "Any amount is much appreciated!"

[shield-total-dl]:  https://img.shields.io/github/downloads/saltssaumure/xp2-discord-theme/total?color=purple&label=Total%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/saltssaumure/xp2-discord-theme/latest/net.saltssaumure.Logarithm.asar?color=purple&label=Replugged%20installs&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/saltssaumure/xp2-discord-theme?style=flat-square "Total size"

[license]:          https://github.com/Saltssaumure/xp2-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/xp2-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/xp2-discord-theme/blob/main/Logarithm.theme.css

[release-gh]:       https://github.com/Saltssaumure/xp2-discord-theme/releases/latest "Latest release"
[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/install?identifier=Saltssaumure/xp2-discord-theme&source=github "Replugged addon installer"

# Logarithm Discord Theme
[![Donate via ko-fi][shield-donate]][ko-fi]
[![Total downloads][shield-total-dl]][release-gh]
[![Replugged installs][shield-asar-dl]][release-gh]
![Total size][shield-repo-size]

***A(nother) Windows XP style Discord theme.***

| Light mode                                                      | Dark mode                                                     |
| --------------------------------------------------------------- | ------------------------------------------------------------- |
| ![Screenshot of Logarithm light mode applied to Discord][light] | ![Screenshot of Logarithm dark mode applied to Discord][dark] |

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the theme file:
    - [GitHub][release-gh]
    - [BD Store][release-bd]
3. Place theme file in BetterDiscord's theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [GitHub][release-gh]
    - [Installer][release-rp]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/xp2-discord-theme/Logarithm.theme.css`

## Customisation

| Description       | Variable name     | Valid values               | Default value |
|-------------------|-------------------|----------------------------|---------------|
| Background colour | `--temp-bg-color` | Any [colour][css-color]. | #000          |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste line 15-25 of [`Logarithm.theme.css`][.theme.css].
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste line 15-25 of [`Logarithm.theme.css`][.theme.css].
4. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
