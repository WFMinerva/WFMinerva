<h1 align="center">HAPPYADONG</h1>

<p align="center">
  Hearts of Iron IV Mod Creator · Historical Biographies · Quality-of-Life Tools · Simplified Chinese Localization
</p>

<p align="center">
  《钢铁雄心4》MOD 作者｜历史人物小传｜便利性与沙盒工具｜简体中文本地化
</p>

<p align="center">
  <a href="https://steamcommunity.com/profiles/76561198024627348">
    <img src="https://img.shields.io/badge/Steam-HAPPYADONG-1b2838?logo=steam&logoColor=white" alt="Steam Profile">
  </a>
  <a href="https://github.com/xADDBx/ToyBox-RogueTrader/pull/63">
    <img src="https://img.shields.io/badge/ToyBox-Official%20Chinese%20Localization-181717?logo=github&logoColor=white" alt="ToyBox Simplified Chinese Localization">
  </a>
</p>

---

## About Me / 关于我

I create and maintain mods for **Hearts of Iron IV**, focusing on historical character biographies, single-player quality-of-life improvements, and sandbox-oriented tools.

I also contribute Simplified Chinese localization to open-source game mod projects.

我主要制作和维护《钢铁雄心4》MOD，方向包括历史人物小传、单人便利性改进和沙盒化工具，同时参与开源游戏 MOD 的简体中文本地化工作。

---

## Featured Projects / 主要作品

### Character Biographies / 钢四人物小传

[![Steam Workshop](https://img.shields.io/badge/Steam-Workshop-1b2838?logo=steam&logoColor=white)](https://steamcommunity.com/sharedfiles/filedetails/?id=3736859636)

Adds historical biographies to national leaders, advisors, army commanders, naval commanders, scientists, and other characters in **Hearts of Iron IV**.

Hover over a character portrait in the game to read their biography and learn about their political position, military career, and historical background.

为《钢铁雄心4》的国家领袖、顾问、陆军将领、海军将领、科学家及其他人物补充悬浮人物小传。

在游戏中将鼠标移动到人物头像上，即可查看其生平、政治立场、军事经历和历史背景。

The project provides separate editions for compatibility-focused play and fuller vanilla coverage.

项目根据使用环境提供轻量兼容版和原版全量版，在人物覆盖范围与兼容性之间作出不同取舍。

---

### One-Click Navy Builder / 一键建设海军

[![Steam Workshop](https://img.shields.io/badge/Steam-Workshop-1b2838?logo=steam&logoColor=white)](https://steamcommunity.com/sharedfiles/filedetails/?id=3765832437)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Source-181717?logo=github&logoColor=white)](https://github.com/WFMinerva/hoi4-one-click-navy)

Adds player-only decisions that instantly construct preset fleets and advanced warships for single-player sandbox campaigns.

The current stable version is **v6.3**. National content includes:

- A modernized main fleet and a commemorative Beiyang Fleet for the Republic of China
- An early People's Liberation Army Navy fleet and a modernized main fleet for Communist China
- A preset Japanese-style fleet for Manchukuo

v6.3 also introduces universal player-only naval construction decisions for:

- British-style advanced destroyers
- Italian-style advanced light cruisers
- German Type XXI advanced submarines

The AI cannot use these decisions. Technologies, ship presets, and delivered ships belong to the country executing the decision; the design-reference countries are not modified.

本项目为单人沙盒战役提供玩家专用决议，可立即建设预设舰队和先进舰艇。

当前稳定版本为 **v6.3**。国家专属内容包括：

- 中华民国现代化主力舰队与北洋水师纪念舰队
- 中国共产党早期人民海军舰队与现代化主力舰队
- 满洲国日式预设舰队

v6.3 同时加入三项全国家玩家通用海军建设决议：

- 英国风格先进驱逐舰
- 意大利风格先进轻巡洋舰
- 德国 XXI 型先进潜艇

AI 不会执行这些决议。所需科技、舰船预设和交付舰艇均归执行国，设计参考国不会因此受到修改。

---

### One-Click Sandbox Start / 开局一键爽玩

[![Steam Workshop](https://img.shields.io/badge/Steam-Workshop-1b2838?logo=steam&logoColor=white)](https://steamcommunity.com/sharedfiles/filedetails/?id=3767025052)

A one-click sandbox setup for the 1936 campaign.

It consolidates a large number of repetitive setup operations into player-only decisions, including technologies, doctrines, appointments, military industrial organizations, equipment designs, division templates, construction, army deployment, and equipment stockpiles.

这是一个面向 1936 年剧本的开局沙盒工具。

它通过玩家专用决议，将科技、学说、人事任命、军工机构、装备设计、师级编制、全国建设、部队部署和装备库存等大量重复操作集中处理，减少控制台命令和手动配置。

Originally developed for Communist China, the project has since been expanded into a broader multi-country version.

该项目最初以中国共产党为基础开发，现已扩展为适用于更多国家的通用版本。

The mod does not pursue game balance. Its purpose is to provide a fast, powerful, and highly customizable sandbox starting point.

本 MOD 不以游戏平衡为目标，而是提供快速、强力且便于继续自定义的沙盒开局。

---

## Localization Contributions / 本地化贡献

### ToyBox for Warhammer 40,000: Rogue Trader

[![Pull Request](https://img.shields.io/badge/GitHub-PR%20%2363-181717?logo=github&logoColor=white)](https://github.com/xADDBx/ToyBox-RogueTrader/pull/63)

Contributed the official Simplified Chinese localization for **ToyBox 2.0.3**.

- Reviewed 921 localization keys
- Translated 713 interface strings
- Preserved English fallback for developer-facing Patch Tool and infrastructure strings
- Verified JSON structure and format placeholders
- Tested the localization in game
- Merged into the upstream repository through Pull Request #63

为《战锤40K：行商浪人》ToyBox 2.0.3 制作简体中文本地化。

- 审核本地化键共 921 项
- 完成简体中文翻译 713 项
- 开发者使用的 Patch Tool 和 Infrastructure 内容主动保留英文回退
- 检查 JSON 结构及格式占位符
- 完成游戏内实机测试
- 通过 Pull Request #63 合并至上游官方仓库的开发分支

---

## Development Principles / 制作原则

My projects generally follow these principles:

- Preserve normal vanilla game progression whenever possible
- Avoid unnecessary changes to unrelated countries or systems
- Separate compatibility-oriented and full-featured editions when necessary
- Keep player-only sandbox tools unavailable to the AI
- Test releases in game before treating them as stable versions
- Prefer historically grounded writing over invented details

我的项目通常遵循以下原则：

- 尽可能不干扰原版游戏的正常进程
- 避免修改无关国家和系统
- 必要时分别提供兼容版与全量版
- 沙盒强化功能仅供玩家使用，不交给 AI
- 经实机测试后再将版本视为稳定基准
- 历史人物文本以公开史料为依据，不随意编造

---

## Links / 相关链接

- [Steam Profile / Steam 个人主页](https://steamcommunity.com/profiles/76561198024627348)
- [Hearts of Iron IV Workshop Items / 我的钢铁雄心4工坊作品](https://steamcommunity.com/profiles/76561198024627348/myworkshopfiles/?appid=394360)
- [Character Biographies / 钢四人物小传](https://steamcommunity.com/sharedfiles/filedetails/?id=3736859636)
- [One-Click Navy Builder / 一键建设海军 — Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3765832437)
- [One-Click Navy Builder / 一键建设海军 — GitHub Source](https://github.com/WFMinerva/hoi4-one-click-navy)
- [One-Click Sandbox Start / 开局一键爽玩](https://steamcommunity.com/sharedfiles/filedetails/?id=3767025052)
- [ToyBox Simplified Chinese Localization / ToyBox 简体中文本地化 PR #63](https://github.com/xADDBx/ToyBox-RogueTrader/pull/63)

---

<p align="center">
  Historical context · Practical tools · Careful localization
</p>

<p align="center">
  历史文本 · 实用工具 · 审慎汉化
</p>
