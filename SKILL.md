---
name: macro-regime-mapping
description: "宏观推演：当用户需要宏观经济复盘、全球宏观情景推演、政策周期分析、大类资产敏感性、通胀/流动性/地缘事件分析、预期差识别、触发条件、失效信号和风险控制框架时使用。输出为非投资建议的结构化宏观研究。"
license: MIT
compatibility: "Requires current macro/market data access for factual updates. Outputs are analytical frameworks only and must not be treated as financial advice."
metadata:
  version: "1.1.0"
  language: "zh-CN"
  display_name: "宏观推演"
---

# 宏观推演

## When to Use This Skill

Use this skill when the user asks to:

- Summarize the current global macro environment or monthly macro changes
- Build a structured macro scenario map for any country, region, or global market
- Analyze inflation, liquidity, fiscal policy, monetary policy, exchange rates, geopolitics, commodities, bonds, equities, or real estate as interacting variables
- Translate macro variables into non-advisory asset-class implications
- Identify expectation gaps, trigger points, invalidation conditions, and follow-up indicators
- Review prior macro calls and update a thesis based on new evidence
- Produce annual or quarterly macro forecasts with clear assumptions, confidence levels, and invalidation criteria

Do not use this skill for personalized financial advice, direct buy/sell instructions, or claims of guaranteed returns.

## Core Principle

Treat macro analysis as a dynamic regime map, not a single forecast. Each output should connect:

1. Current state and the dominant macro axis
2. Key drivers and stakeholder incentives
3. Transmission channels
4. Data anchors and policy signals
5. Scenario branches
6. Asset-class sensitivity
7. Confirmation and invalidation signals
8. Risk controls and uncertainty

## Required Workflow

### 1. Define the Time Window and Output Mode

Clarify the observation window:

- Monthly review
- Quarterly outlook
- Event-driven update
- Annual scenario map
- Asset-specific follow-up

If the user does not specify a window, default to the current month and the next one to three quarters.

Then identify the output mode:

- Review mode: explain what changed and why
- Forecast mode: state directional conclusions with assumptions and confidence levels
- Shock mode: analyze event transmission and second-order effects
- Thesis-check mode: test a user's claim against data, policy, positioning, and counterarguments

### 2. Identify the Dominant Macro Axis

Start by asking which structural force is currently driving the system:

- Central-bank rate cycle: tightening, pause, easing, or re-acceleration
- Dollar liquidity and credit cycle: expansion, contraction, refinancing stress, or reserve reallocation
- Fiscal cycle: stimulus, austerity, front-loading, debt-service pressure, or deficit constraint
- Geopolitical or trade-order shift: globalization, fragmentation, tariffs, sanctions, supply-chain relocation
- Debt and balance-sheet cycle: leverage expansion, deleveraging, refinancing wall, collateral stress
- Technology or industrial narrative: AI capex, energy transition, industrial upgrading, productivity shock

Treat local variables as downstream functions of the dominant axis unless there is strong evidence of local decoupling. Explicitly state what would mark a regime switch.

### 3. Separate Hard Data from Narrative

Classify inputs into:

- Hard data: inflation, PMI, GDP, employment, fiscal issuance, credit, property sales, trade, inventories, interest rates, exchange rates
- Policy signals: central bank language, fiscal stance, regulatory intervention, industrial policy, election incentives
- Market behavior: price action, factor rotation, flows, leverage, positioning, sentiment
- Narrative: consensus stories, media framing, market slogans, geopolitical rhetoric

Give higher weight to data, policy constraints, and cross-asset confirmation than to narratives.

### 4. Build the Domestic or Regional Macro Block

For domestic or region-specific analysis, cover the relevant local variables:

- Fiscal impulse: government bond issuance pace, front-loading, local-government capacity, debt-service pressure
- Monetary and credit conditions: rate-cut probability, liquidity, social financing, deposit rates, bank behavior
- Inflation and industrial prices: CPI, PPI, upstream/downstream pass-through, commodity cost pressure
- Real estate: transaction volume, price trend, city-tier divergence, policy stimulus, supply-demand balance
- Three growth engines: export, investment, consumption
- Corporate profit structure: which sectors drive earnings improvement, whether profit recovery is broad or narrow

Always ask whether price recovery is demand-driven, cost-driven, or liquidity-driven.

### 5. Build the External Macro Block

For global analysis, cover:

- US cycle: inflation, employment quality, household balance sheet, fiscal impulse, Fed reaction function, political calendar
- Japan cycle: fiscal expansion, bond yields, yen pressure, equity-market policy support, inflation persistence
- Other regions: energy sensitivity, trade relations, industrial competitiveness, political risk
- Geopolitics: conflict probability, escalation path, negotiation incentives, supply-chain impact
- Cross-border flows: dollar strength, reserve allocation, capital flight or repatriation, trade settlement behavior

Treat political events as economic incentives with deadlines, stakeholders, and negotiation payoffs.

### 6. Analyze Stakeholder Incentives

For each major policy or event question, list the relevant stakeholders and constraints:

- Government or fiscal authority: growth target, employment, debt service, social stability, election or term horizon
- Central bank: inflation target, currency stability, financial stability, credibility, political pressure
- Enterprises: margins, inventory, financing cost, export orders, capex incentives
- Households: income expectation, debt burden, wealth effect, consumption willingness
- Foreign capital or external counterparties: yield spread, geopolitical risk, hedging cost, exit constraints

Do not predict personal psychology. Infer likely behavior from incentives, constraints, and available choices.

### 7. Map Transmission Channels

Use explicit causal chains. Examples:

- Export strength → trade surplus → settlement demand → currency appreciation pressure → exporter margin pressure
- Government-bond front-loading → early-year investment support → mid-year fiscal fade → growth slowdown risk
- Energy shock → input costs → CPI/PPI split → central-bank reaction → bond yield repricing
- Geopolitical shock → risk-off flows → safe-haven demand → liquidity tightening → leveraged-asset drawdown
- Upstream commodity rally → downstream margin compression → production slowdown → rally sustainability test

Avoid isolated conclusions that do not show the mechanism.

### 8. Anchor with Data and Pricing

Use data to locate the current stage and remaining space, not to create false point precision:

- Stock versus flow: debt/GDP, housing inventory, credit stock, fiscal balance
- Rate of change: acceleration, deceleration, inflection, base effect
- Historical percentile: valuation, yield, spread, volatility, inventory
- Policy rate versus market-implied rate: whether easing/tightening is already over-priced
- Supply-demand gap: new supply, inventory digestion, replacement demand, subsidy pull-forward

When market pricing has fully discounted a story, treat the story as vulnerable even if the direction is logically correct.

### 9. Decode Policy Signals

Read policy through actions, omissions, and implementation details:

- Additive signal: a new policy reveals the problem being prioritized
- Subtractive signal: a stopped or missing policy reveals what is being abandoned or deprioritized
- Action versus rhetoric: when words conflict with implementation, prioritize actions
- Preparatory signal: small technical measures may be laying the groundwork for larger regime changes

Do not over-read slogans. Tie every policy interpretation to budget constraints, enforcement capacity, and observed follow-through.

### 10. Create Scenario Branches

For each major uncertainty, produce 2-4 branches:

- Base case
- Upside surprise
- Downside surprise
- Tail risk, if relevant

For every branch, state:

- Probability as qualitative or broad percentage bands if the user requests probabilities
- Trigger conditions
- Expected macro result
- Asset-class implications
- Invalidation signal

Never present one scenario as inevitable.

### 11. Analyze Asset-Class Sensitivity

Translate macro conclusions into asset-class sensitivity, not direct investment advice:

- FX: interest-rate differentials, trade surplus, settlement behavior, safe-haven flow, policy tolerance
- Bonds: growth slowdown, inflation pressure, supply-demand balance, central-bank reaction function
- Equities: earnings breadth, liquidity, policy support, valuation, leverage, factor rotation
- Commodities: physical supply-demand, financial speculation, inventory, geopolitical premium, pass-through ability
- Real estate: policy easing, mortgage rates, supply, household income expectations, city-tier divergence
- Defensive yield assets: dividend durability, bond-like valuation, rate alternatives, crowding risk

Use the language of “sensitivity,” “watch points,” and “risk-reward,” not “must buy” or “must sell.”

### 12. Identify Expectation Gaps

Look for gaps between market consensus and observable constraints:

- Consensus expects policy easing, but policy language suggests restraint
- Market prices conflict escalation, but actors have incentives to negotiate
- Commodity prices imply demand boom, but downstream orders and inventories do not confirm it
- Equity rally assumes broad earnings recovery, but profits are concentrated in a few sectors
- Safe-haven asset fails to rise during stress, indicating that its regime may have changed

Expectation gaps should include both the opportunity and the reason they may be wrong.

### 13. Add Forecast Discipline and Risk Controls

Every output with asset implications must include:

- What would prove the thesis wrong
- Which data should be monitored next
- Which part is high confidence and which part is speculative
- Direction confidence and timing confidence separately when making forecasts
- Key assumptions and their fragility
- Whether the asset is driven by fundamentals, liquidity, policy, or crowd behavior
- A reminder that this is not personalized financial advice

For leveraged, futures, options, or inverse products, explicitly warn that they can suffer rapid losses and are unsuitable for most users.

When the user asks for explicit predictions, use this format:

```text
【判断】一句话给出方向性结论
【核心逻辑】1-3 条因果链
【关键前提】该判断成立所需的必要条件
【失效条件】什么证据会证伪该判断
【置信度】方向置信度：高/中/低；时间节点置信度：高/中/低
```

## Output Templates

### Monthly Macro Review

Use this structure:

1. Executive summary: three to five key changes
2. Domestic block: fiscal, monetary, inflation, property, trade, consumption/investment
3. Global block: US, Japan, Europe, geopolitics, dollar/liquidity
4. Asset sensitivity map: FX, bonds, equities, commodities, real estate/yield assets
5. Scenario table: base/upside/downside/tail risk
6. Watchlist: next data releases, policy meetings, events, invalidation signals
7. Risk disclaimer

### Event Shock Analysis

Use this structure:

1. Event summary and immediate market reaction
2. Actual economic transmission versus emotional pricing
3. Stakeholder incentives and negotiation path
4. Scenario branches with triggers
5. Asset sensitivity and likely second-order effects
6. What would change the conclusion

### Asset Thesis Check

Use this structure:

1. Asset and current consensus
2. Macro drivers supporting the thesis
3. Macro drivers against the thesis
4. Cross-asset confirmation or contradiction
5. Trigger/invalidation checklist
6. Risk-reward assessment without direct advice

## Reference Loading

Read `references/methodology.md` when:

- The user asks for a full framework, reusable methodology, or detailed report
- The task involves multiple countries or multiple asset classes
- The output needs a scenario table, watchlist, or investment-style review

Read `references/reasoning-framework.md` when:

- The user asks for annual forecasts, quarterly predictions, or explicit directional calls
- The output needs stakeholder incentives, data anchoring, policy-signal decoding, or confidence grading
- The task involves distinguishing trend direction from timing or identifying common reasoning biases

## Style Guide

- Respond in the user's language when possible, and support bilingual Chinese-English outputs when useful.
- Be structured, concise, and explicit about causal chains.
- Use tables when comparing scenarios, variables, or assets.
- Do not imitate any creator’s personal voice, catchphrases, paywall structure, or identity.
- Avoid sensational language. Replace certainty with conditional reasoning.
- Cite current external data sources when using web or finance tools.

## Safety Boundary

This skill provides macro research and educational analysis only. It does not provide personalized investment advice, portfolio management, tax advice, or trading instructions.
