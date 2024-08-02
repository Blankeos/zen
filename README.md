<p align="middle">
  <img src="https://raw.githubusercontent.com/Blankeos/zen/main/assets/icon.svg" width="150"  />
  <h3 align="middle">Blankeos Zen</h3>
  <p align="middle">A minimal, dark, and frameless theme for VS Code. Based on poimandres.</p>
</p>

<div align="middle">
<img src="https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat">
<img src="https://img.shields.io/badge/version-0.0.2-brightgreen.svg?style=flat">
</div>

<br />

<p align="middle">
  <img src="https://raw.githubusercontent.com/Blankeos/zen/main/assets/screencap.jpg" />
</p>

**Blankeos Zen** is essentially a **_blue [poimandres](https://github.com/drcmda/poimandres-theme)_**. It's my own personal, minimal, and frameless dark-theme. Sometimes I don't feel the green in poimandres and wanted a bluer vibe to my editor. That's why I made this.

This theme contains:

- Blankeos Zen - a bluer poimandres
- Blankeos Zen Dark - a bluer poimandres but darker

---

#### Development Requirements & Tips

- Use [Bun](bun.sh)
- Install [`vsce`](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) (for packaging & publishing the extension)
- Refer to this [vid](https://www.youtube.com/watch?v=pGzssFNtWXw) on how to publish:

  ```sh
  vsce login <publisher name>
  vsce package
  vsce publish
  ```

#### Contribute

    git clone https://github.com/Blankeos/zen
    cd zen
    bun install
    bun run dev

Go to `Run and Debug`, click the ▶ icon, any change you make in `src/theme.js` will now be reflected when you save.

<!-- ## Related

- [poimandres-alacritty][poimandres-alacritty]: Alacritty version
- [poimandres-iterm][poimandres-iterm]: Iterm version
- [poimandres-kitty][poimandres-kitty]: Kitty version
- [poimandres-nvim][poimandres-nvim]: Neovim version
- [poimandres-jetbrains][poimandres-jetbrains]: JetBrains version

[poimandres-alacritty]: https://github.com/z0al/poimandres-alacritty
[poimandres-iterm]: https://github.com/alii/poimandres-iterm
[poimandres-kitty]: https://github.com/guilhermedeandrade/poimandres-kitty
[poimandres-nvim]: https://github.com/olivercederborg/poimandres.nvim
[poimandres-jetbrains]: https://github.com/marko-mihajlovic/poimandres-jetbrains

### Hyper theme

```bash
hyper i hyper-pmndrs
``` -->
