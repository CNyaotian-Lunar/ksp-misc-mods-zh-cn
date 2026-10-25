# KSP 杂项模组汉化合集 简体中文补丁

为《坎巴拉太空计划》(KSP) 的 **杂项模组汉化合集** 提供简体中文本地化，共 115 条本地化条目。

**本仓库只包含翻译文本。不包含任何原模组的模型、纹理、代码或配置。使用前请自行安装对应模组。**

A Simplified Chinese localization for **杂项模组汉化合集** (KSP), 115 localization entries in total.

**This repository contains translation text only. You must install the original mods separately.**

---

## 覆盖范围 / Scope

| 文件 / File | 条目 / Entries | 对应模组 / Mod | 许可 / License |
|---|---|---|---|
| `NavyFish-zh-cn.cfg` | 27 | Docking Port Alignment Indicator | MIT |
| `PersistentThrust-zh-cn.cfg` | 23 | PersistentThrust | MIT |
| `DatedQuickSaves-zh-cn.cfg` | 23 | Dated QuickSaves | GPL-3.0 |
| `MoarKerbalsParts-zh-cn.cfg` | 22 | MoarKerbalsParts | CC BY-NC-SA 4.0 |
| `ImprovedTreeEnginePlacement-zh-cn.cfg` | 16 | ImprovedTreeEnginePlacement | CC BY-NC 4.0 |
| `BluedogDB-zh-cn.cfg` | 4 | Bluedog Design Bureau（资源文本部分） | CC BY-NC-SA 4.0 |

---

## 安装 / Installation

1. 确认已安装对应模组。
2. 将本仓库的 `GameData/0001_Misc_CN/` 目录复制到 KSP 安装目录的 `GameData/` 下。
3. 启动游戏，语言设为简体中文。

1. Make sure the original mods are installed.
2. Copy `GameData/0001_Misc_CN/` into your KSP `GameData/` directory.
3. Launch the game with language set to Simplified Chinese.

本补丁尚未收录进 CKAN，请使用手动安装。CKAN listing is not available yet.

---

## 翻译约定 / Translation conventions

- 各文件的许可见上表，互不覆盖
- 品牌与零件代号保留英文
- 格式控制符原样保留（`\n` `^N` `<i>` `</i>` `<br>` `<color=...>`）
- 纯代码标识符、资源 ID、贴图路径一律不动
- Format control sequences, code identifiers, resource IDs and asset paths are left untouched.

---

## 兼容性 / Compatibility

- 游戏版本 / Game version：KSP 1.12.5

---

## 已知问题 / Known issues

- 上游新增文本时对应条目回退英文，等待本补丁同步。
- 翻译由 AI 辅助初翻，格式、条目完整性与术语一致性经过程序校验；个别语句可能生硬，欢迎在 issue 报告（请注明 localization key）。
- New upstream strings fall back to English until this patch is updated.
- Translation was produced with AI assistance and machine-verified.

---

## 许可 / License

各文件适用各自的许可，见上方表格。
详见 `LICENSE`。 See `LICENSE`.

### 致谢 / Credits

- 各自作者（见下表）
- 翻译与校验 / Translation and verification：CNyaotian-Lunar

---

## 贡献 / Contributing

发现翻译错误请开 issue，注明对应的 localization key。上游更新后同步新条目的 PR 欢迎。
Open an issue for translation errors with the localization key. PRs syncing new upstream entries are welcome.
