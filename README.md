# Major Partnership Insider

## 中文介绍

**Major Partnership Insider（重大合作内幕线索调查）** 是一个用于研究上市公司是否可能在未来 30-120 天内发布重大合作、核心客户签约、战略联盟、租赁协议、合资、并购或业务转型公告的 Codex Skill。

它的核心思路不是依赖单一传闻，而是把 **期权异动、机构持仓、SEC 文件、经营动作、招聘/CapEx、行业日程** 放到同一条证据链中交叉验证，最后输出一个概率区间、可能事件类型、公告时间窗口和风险情景。

### 适用场景

- 发现某家公司出现异常大额期权交易，想判断是否可能指向重大合作。
- 想研究激进投资者、做市机构或量化基金的异常增持是否具有催化剂含义。
- 想从招聘、建设、采购、CapEx、项目进度中寻找潜在客户签约前的经营证据。
- 想把期权到期日、财报、行业会议、财政年末等时间点整合成公告窗口判断。

### 逻辑链路

1. **期权异动识别资金意图**  
   分析大额、单向、价外 Call 买入，高 IV 下仍然激进买入，Vol/OI 异常，滚仓、上移行权价、缩短到期时间等信号。

2. **机构持仓验证独立共振**  
   检查 13F/13G/13D 中激进投资者、量化基金、做市商或战略投资者是否同步异常增持。重点是“独立信号汇聚”，不是假设串谋。

3. **经营动作寻找实体证据**  
   追踪 CapEx、建设、采购、招聘、许可证、技术售前、供应链和交付岗位。强信号通常是：如果没有潜在大客户或重大合作，这些动作会显得不经济。

4. **SEC 文件排查反证风险**  
   检查 8-K、S-3、424B、ATM、Form 4、10-Q/10-K 等文件，识别融资稀释、内幕卖出、项目延期、流动性压力和客户集中风险。

5. **时间窗口对齐公告概率**  
   将期权到期日、财报、投资者会议、行业大会、项目交付节点和财政年末放到一张时间线上，判断多个信号是否集中在同一个 2-6 周窗口。

6. **输出概率与情景推演**  
   给出总体概率、可能合作类型、预计公告窗口、Bull/Base/Bear 三种情景，以及失效条件和后续监控清单。

### 输出结果

该 skill 会生成结构化报告，包括：

- 总体概率区间
- 可能的重大合作或战略事件类型
- 预计公告时间窗口
- 证据矩阵
- 期权与 gamma/delta 解读
- 机构与经营证据分析
- Bull/Base/Bear 情景
- 反证、风险与失效条件

> 本 skill 只使用公开信息或用户提供的数据进行概率研究，不构成投资建议，也不用于判断或指控真实内幕交易。

---

## English Introduction

**Major Partnership Insider** is a Codex Skill for investigating whether a public company may announce a major partnership, anchor customer contract, strategic alliance, lease agreement, joint venture, M&A transaction, restructuring, or business-model transformation within the next 30-120 days.

Instead of relying on rumors or a single unusual trade, it cross-validates **options anomalies, institutional filings, SEC disclosures, operational signals, hiring/CapEx activity, and catalyst calendars** into one evidence chain. The final output is a probabilistic research report with an estimated probability range, likely event type, announcement window, and key risks.

### When To Use

- A company shows unusual large options activity and you want to assess whether it may point to a major partnership.
- Activist investors, market makers, quant funds, or strategic holders appear to be accumulating shares unusually.
- Hiring, construction, procurement, CapEx, or project milestones suggest preparation for a large customer or strategic deal.
- You want to align options expirations, earnings, conferences, fiscal deadlines, and project milestones into a possible announcement window.

### Logic Chain

1. **Decode Derivatives Intent**  
   Analyze large, directional, OTM call buying, aggressive buying under high implied volatility, abnormal Vol/OI, roll-ups, time compression, and strike migration.

2. **Validate Institutional Convergence**  
   Review 13F/13G/13D filings for activist pressure, quant or market-maker accumulation, and strategic holder activity. The focus is independent signal convergence, not assumed coordination.

3. **Find Operational Evidence**  
   Track CapEx, construction, procurement, permits, hiring, technical pre-sales, supply chain, and delivery-readiness signals. Strong evidence often appears when a company acts in ways that would be economically unusual without a likely customer or partner.

4. **Check SEC Filings For Contradictions**  
   Review 8-K, S-3, 424B, ATM programs, Form 4, 10-Q, and 10-K disclosures to identify dilution, insider selling, project delays, liquidity risks, and customer concentration risks.

5. **Align The Timeline**  
   Compare options expirations, earnings dates, investor events, industry conferences, fiscal year-end, regulatory deadlines, and project milestones to see whether multiple signals converge into the same 2-6 week window.

6. **Produce Probability And Scenarios**  
   Output an overall probability range, likely event type, expected announcement window, Bull/Base/Bear scenarios, invalidation triggers, and a monitoring checklist.

### Output

The skill produces a structured report containing:

- Overall probability range
- Likely partnership or strategic event type
- Expected announcement window
- Evidence matrix
- Options and gamma/delta interpretation
- Institutional and operational evidence analysis
- Bull/Base/Bear scenarios
- Risks, contradictions, and invalidation triggers

> This skill uses only public information or user-provided data for probabilistic research. It is not investment advice and should not be used to allege actual insider trading.
