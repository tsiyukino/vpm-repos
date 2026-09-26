# TsiYuki VPM Listing

VPM package listing for TsiYuki's VRChat tools.

**Add to VCC / ALCOM:** open <https://tsiyukino.github.io/vpm-repos/> and click *Add to VCC*, or add this URL manually:

```
https://tsiyukino.github.io/vpm-repos/index.json
```

| Package | What it does | Repository |
| --- | --- | --- |
| `moe.tsiyuki.wardrobe` | Outfit and hair switcher: exclusive outfits with piece toggles, colours and looks, absorbing the menus that ship inside outfits | [YukiWardrobe](https://github.com/tsiyukino/YukiWardrobe) |
| `moe.tsiyuki.material` | Non-destructive material editing: edit a material through its own shader inspector, or merge images into its textures, without duplicating anything into your project | [YukiMaterial](https://github.com/tsiyukino/YukiMaterial) |
| `moe.tsiyuki.menu` | Shows the menu your avatar actually ends up with, and lets you set its order and how many items sit on a wheel | [YukiMenu](https://github.com/tsiyukino/YukiMenu) |
| `moe.tsiyuki.follow` | Keeps objects (SPS sockets, charms) on a mesh surface while its blendshapes change, makes outfits follow the body's blendshapes, and blends a separate body part's seam into the body's shading | [YukiFollow](https://github.com/tsiyukino/YukiFollow) |
| `moe.tsiyuki.nontoon` | lilToon to NonToon conversion at build time | [YukiNonToon](https://github.com/tsiyukino/YukiNonToon) |
| `moe.tsiyuki.core` | Shared editor code every tool builds on | [YukiCore](https://github.com/tsiyukino/YukiCore) |
| `moe.tsiyuki.core.animation` | Animator building blocks for tools that generate FX layers | [YukiCoreAnimation](https://github.com/tsiyukino/YukiCoreAnimation) |
| `moe.tsiyuki.core.texture` | Texture compositing for tools that bake textures and materials | [YukiCoreTexture](https://github.com/tsiyukino/YukiCoreTexture) |
| `moe.tsiyuki.core.menus` | Modular Avatar menu building and placement for tools that generate menus | [YukiCoreMenus](https://github.com/tsiyukino/YukiCoreMenus) |

## How it works

This repository contains no packages. `source.json` lists the plugin repositories; the
`Build Repo Listing` workflow collects the release zips from those repositories and publishes
`index.json` plus a small web page to GitHub Pages. Each plugin repository triggers this
workflow after publishing a release.

---

# TsiYuki VPM 源

TsiYuki 的 VRChat 工具的 VPM 源。在 VCC / ALCOM 中添加上面的地址即可安装和更新所有插件。
本仓库不包含插件本身，只负责汇总各插件仓库的 Release 并发布到 GitHub Pages。
