# 🧭 Macro Regime Mapping / 宏观情景罗盘

一个用于宏观周期、政策变量、地缘事件与大类资产敏感性分析的 Agent Skill。

它把宏观分析拆成「变量识别 → 传导链条 → 情景分支 → 资产敏感性 → 触发/失效条件 → 风险控制」的可复用工作流，适合月度宏观复盘、事件冲击分析、资产观点检查和投资研究笔记。

## 生态 / Ecosystem

This repository follows the Agent Skills open format: a skill is a folder containing a required `SKILL.md`, with optional `references/`, `scripts/`, and `assets/` for progressive disclosure.

Compatible with agents or platforms that support the Agent Skills convention.

## 安装 / Install

```bash
npx skills add <owner>/macro-regime-mapping
```

将 `<owner>` 替换为你的 GitHub 用户名或组织名。

<details>
<summary>Manual install</summary>

Download or clone this repository, then place the folder in your agent’s skills directory, for example:

```text
~/.agents/skills/macro-regime-mapping/
```

The folder name and the `name` field in `SKILL.md` must both be `macro-regime-mapping`.

</details>

## 什么时候使用 / When to Use

Use this skill when you ask an agent to:

- 做月度宏观经济复盘，梳理不同国家、地区与主要经济体的变量变化
- 分析财政、货币、通胀、地产、出口、地缘冲突、汇率和流动性之间的传导关系
- 把宏观变量映射到汇率、债券、股票、大宗商品、地产、红利资产等大类资产敏感性
- 构建 base / upside / downside / tail risk 情景表
- 找预期差、触发条件、失效条件和后续跟踪指标
- 复盘之前的宏观判断，并根据新证据更新观点

## 使用示例 / Examples

```text
用 macro-regime-mapping 帮我做一份 2026 年 4 月全球宏观月度复盘，重点看主要经济体财政变化、美国通胀、油价和主要货币。
```

```text
分析一下如果中东冲突缓和，原油、黄金、美债、人民币和 A 股分别会受到什么影响。给我情景分支和失效条件。
```

```text
检查我的观点：今年某一经济体通胀会回升，本地债券逻辑可能反转。请按变量、传导链、支持证据、反对证据和跟踪指标拆解。
```

```text
做一个非投资建议版的大类资产敏感性表：人民币、美债、中债、日经、A 股、黄金、原油。
```

## 能力边界 / Capabilities

| 模块 | 能做什么 | 注意事项 |
| --- | --- | --- |
| 宏观复盘 | 按月或按事件梳理关键变量变化 | 需要实时数据时应联网或调用金融数据工具 |
| 国内周期 | 分析财政、货币、通胀、地产、出口、消费和投资 | 不把单月数据机械外推 |
| 全球周期 | 分析美国、日本、欧洲和地缘事件 | 区分真实经济冲击与情绪定价 |
| 传导链 | 将变量连接成因果链 | 避免孤立结论 |
| 情景分支 | 输出 base/upside/downside/tail risk | 每个情景都应有触发和失效条件 |
| 资产敏感性 | 讨论 FX、债券、权益、大宗、红利资产 | 不输出个性化买卖建议 |
| 预期差 | 找市场共识与数据/政策约束之间的偏差 | 必须说明为什么可能判断错误 |
| 风险控制 | 标注高风险工具、杠杆、期货、波动风险 | 高风险产品需明确警示 |

## 输出结构 / Output Structure

<details>
<summary>月度宏观复盘模板</summary>

1. Executive summary: three to five key changes
2. Domestic block: fiscal, monetary, inflation, property, trade, consumption/investment
3. Global block: US, Japan, Europe, geopolitics, dollar/liquidity
4. Asset sensitivity map: FX, bonds, equities, commodities, real estate/yield assets
5. Scenario table: base/upside/downside/tail risk
6. Watchlist: next data releases, policy meetings, events, invalidation signals
7. Risk disclaimer

</details>

<details>
<summary>事件冲击分析模板</summary>

1. Event summary and immediate market reaction
2. Actual economic transmission versus emotional pricing
3. Stakeholder incentives and negotiation path
4. Scenario branches with triggers
5. Asset sensitivity and likely second-order effects
6. What would change the conclusion

</details>

<details>
<summary>资产观点检查模板</summary>

1. Asset and current consensus
2. Macro drivers supporting the thesis
3. Macro drivers against the thesis
4. Cross-asset confirmation or contradiction
5. Trigger/invalidation checklist
6. Risk-reward assessment without direct advice

</details>

## 方法论 / Methodology

The detailed framework lives in:

```text
references/methodology.md
```

Agents should load it when producing full reports, multi-country analysis, multi-asset scenario tables, or recurring macro reviews.

## 目录结构 / Repository Structure

```text
macro-regime-mapping/
├── SKILL.md
├── README.md
├── LICENSE
└── references/
    └── methodology.md
```

## 免责声明 / Disclaimer

This skill is for educational macro research only. It does not provide personalized investment advice, portfolio management, trading instructions, tax advice, or guaranteed forecasts. Users should independently verify data and evaluate their own risk tolerance before making financial decisions.

本 Skill 仅用于宏观研究与教育分析，不构成个性化投资建议、交易指令、税务建议或收益承诺。涉及期货、杠杆、期权、反向产品等高风险工具时，应特别注意快速亏损与流动性风险。

## License

MIT
