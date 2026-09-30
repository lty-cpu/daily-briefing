# daily-briefing · 每日关注

中文财经研究简报 Skill，覆盖 A股、宏观与 AI，生成可离线阅读的单文件 HTML。此仓库统一保存历次发行包与版本记录。

## 版本与下载

当前稳定版：v4.3。v4.4 为开发测试版，真实研究覆盖与正常耗时验收尚未完全通过。

| 顺序 | 版本 | 状态 |
|---|---|---|
| 01 | [v1.0](https://github.com/lty-cpu/daily-briefing/releases/tag/v1.0) | 历史发行 |
| 02 | [v1.1](https://github.com/lty-cpu/daily-briefing/releases/tag/v1.1) | 历史发行 |
| 03 | [v1.2](https://github.com/lty-cpu/daily-briefing/releases/tag/v1.2) | 历史发行 |
| 04 | [v1.3](https://github.com/lty-cpu/daily-briefing/releases/tag/v1.3) | 历史发行 |
| 05 | [v2.0](https://github.com/lty-cpu/daily-briefing/releases/tag/v2.0) | 历史发行 |
| 06 | [v2.1](https://github.com/lty-cpu/daily-briefing/releases/tag/v2.1) | 历史发行 |
| 07 | [v3.0](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.0) | 历史发行 |
| 08 | [v3.1](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.1) | 历史发行 |
| 09 | [v3.2](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.2) | 历史发行 |
| 10 | [v3.3](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.3) | 历史发行 |
| 11 | [v3.4](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.4) | 历史发行 |
| 12 | [v3.4-layout](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.4-layout) | 历史发行 |
| 13 | [v3.5-editorial](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.5-editorial) | 历史发行 |
| 14 | [v3.6-sol-quality-time](https://github.com/lty-cpu/daily-briefing/releases/tag/v3.6-sol-quality-time) | 历史发行 |
| 15 | [v4.0](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.0) | 历史发行 |
| 16 | [v4.0-observation-update](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.0-observation-update) | 历史发行 |
| 17 | [v4.0.1-network-permission](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.0.1-network-permission) | 历史发行 |
| 18 | [v4.0.2](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.0.2) | 历史发行 |
| 19 | [v4.2-first-release](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.2-first-release) | 历史变体 |
| 20 | [v4.2-before-readable](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.2-before-readable) | 历史变体 |
| 21 | [v4.2-before-layout](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.2-before-layout) | 历史变体 |
| 22 | [v4.2](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.2) | 历史发行 |
| 23 | [v4.3](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.3) | 历史发行 |
| 24 | [v4.4](https://github.com/lty-cpu/daily-briefing/releases/tag/v4.4) | 开发测试版 |

首发 ZIP 没有显式版本号，本仓库以 v1.0 作为存档顺序，不改写原 Skill 声明；不存在的版本不补造。

## 使用

1. 从对应 Release 下载 ZIP，解压后使用其中的 daily-briefing 文件夹。
2. 按该版本的 SKILL.md 配置到支持 Skill 的 Agent 宿主。历史版本能力与命令不同。
3. 本地资料库和可选数据源凭据另行配置，不属于公开发行包。

packages/ 保存历次发行 ZIP；按旧到新导入，每个版本对应一条提交和一个 Tag。标签与提交时间是本次集中导入时间，不冒充原版当时的发布时间。

## 发布边界

- 仅使用预先生成的发行 ZIP 和明确标注的历史 ZIP 变体，不从本机安装的 Codex / DSH Skill 目录打包。
- 本机 API 密钥、local_config、账号配置、真实报告档案、行情缓存、运行工件和日志不上传。
- 早期对比包只保留 Skill 本体，移除外层研究和评测资料；包内开发测试材料剔除，纯教学示例保留。本机原 ZIP 不修改。
- SHA-256 和清理记录见 releases.json；重复副本按内容去重。
- 当前仓库的历史版本集中导入尚在进行，版本链接在对应 Release 发布后生效。

## 研究边界

报告用于研究观察。消息可报道性、事实确认和分析输入分别判断，计划发布不等于已经执行。研究规则及未校准概率不构成经验证的交易策略或投资建议。
