# TsiYuki VPM Listing

VPM package listing for TsiYuki's VRChat tools.

**Add to VCC / ALCOM:** open <https://tsiyukino.github.io/vpm-repos/> and click *Add to VCC*, or add this URL manually:

```
https://tsiyukino.github.io/vpm-repos/index.json
```

| Package | Repository |
| --- | --- |
| `moe.tsiyuki.core` | [YukiCore](https://github.com/tsiyukino/YukiCore) |
| `moe.tsiyuki.wardrobe` | [YukiWardrobe](https://github.com/tsiyukino/YukiWardrobe) |
| `moe.tsiyuki.nontoon` | [YukiNonToon](https://github.com/tsiyukino/YukiNonToon) |

## How it works

This repository contains no packages. `source.json` lists the plugin repositories; the
`Build Repo Listing` workflow collects the release zips from those repositories and publishes
`index.json` plus a small web page to GitHub Pages. Each plugin repository triggers this
workflow after publishing a release.

---

# TsiYuki VPM 源

TsiYuki 的 VRChat 工具的 VPM 源。在 VCC / ALCOM 中添加上面的地址即可安装和更新所有插件。
本仓库不包含插件本身，只负责汇总各插件仓库的 Release 并发布到 GitHub Pages。
