# Agent Trust Source Dossier

**Project:** Related-work section — *how people place their trust in AI agents that search and use tools on their behalf*
**Purpose:** Verified source dossier for co-author review before the Friday deadline. Bilingual (English / 中文).
**Status:** Draft for review.

---

## 1. Papers Found (arXiv scans from two angles)

Two arXiv literature searches were run: (A) the phrase **"tool use agents"** and (B) **"human trust in conversational search agents"**. Each returned **5 papers**, for **10 papers total**. IDs and titles are reproduced exactly as returned by the searches. Papers marked **[DEEP-READ]** had their full text retrieved and analyzed, not just their abstracts.

### Search A — "tool use agents"

| # | arXiv ID | Title (as returned) | One-line takeaway |
|---|----------|--------------------|-------------------|
| 1 | 2604.03465 | The Tool Illusion: Rethinking Tool Use in Web Agents | **[DEEP-READ]** An extensive controlled study across tool sources, five backbone models, three tool-use frameworks, and two web benchmarks that revises prior claims: LLM-synthesized tools mainly help via "one-way capability distillation" (only when the tool user is weaker than the synthesizer), overly comprehensive tools can hurt generalization, and tools carry hidden token/action costs. |
| 2 | 2602.20426 | Learning to Rewrite Tool Descriptions for Reliable LLM-Agent Tool Use | Trace-Free+, a curriculum-learning framework that rewrites tool descriptions for agents rather than for human developers, cutting accuracy degradation by 29.23% and improving query-level success by 60.89% on StableToolBench as catalogs scale to 150+ tools. |
| 3 | 2604.00835 | Agentic Tool Use in Large Language Models | A survey that consolidates the fragmented tool-use literature into three paradigms — prompting-as-plug-and-play, supervised tool learning, and reward-driven tool policy learning — analyzing methods, strengths, failure modes, and evaluation. |
| 4 | 2601.22037 | Optimizing Agentic Workflows using Meta-tools | Agent Workflow Optimization (AWO) mines workflow traces to bundle recurring tool-call sequences into deterministic meta-tools, reducing LLM calls up to 11.9% while raising task success by up to 4.2 percentage points. |
| 5 | 2511.01854 | Tool-to-Agent Retrieval: Bridging Tools and Agents for Scalable LLM Multi-Agent Systems | A shared-embedding retrieval framework that represents individual tools and their parent agents (including MCP servers) for fine-grained routing, improving Recall@5 by 19.4% and nDCG@5 by 17.7% on LiveMCPBench. |

### Search B — "human trust in conversational search agents"

| # | arXiv ID | Title (as returned) | One-line takeaway |
|---|----------|--------------------|-------------------|
| 6 | 2608.21177 | From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search | **[DEEP-READ]** Two mixed-methods studies (N=21 and N=20) show significantly higher trust in ChatGPT-sourced health information than Google, and that trust shifts significantly across text-, speech-, and embodied dissemination interfaces, driven by source credibility, search autonomy, prior knowledge, and interaction style/modality. |
| 7 | 2403.09987 | Trusting the Search: Unraveling Human Trust in Health Information from Google and ChatGPT | **[DEEP-READ]** A within-subjects lab study (N=21) finding trust in ChatGPT significantly higher than Google for health information, a trust-information ↔ trust-agent correlation that holds only for Google, no task-type effect, and prior knowledge, presentation style, and interactive manner as key trust determinants. |
| 8 | 2404.19291 | Dynamic Human Trust Modeling of Autonomous Agents With Varying Capability and Strategy | **[DEEP-READ]** With 80 subjects in a human-autonomy-teaming search task, time-series (ARIMAX) models beat static OLS, showing the temporal ordering of agent performance and recency bias drive how trust in autonomous agents evolves. |
| 9 | 2010.04885 | Towards a Conversational Measure of Trust | Proposes a nondirective, conversational (dialogue-based) instrument to measure trust in agents continuously and unobtrusively, overcoming the limitations of one-shot Likert surveys in dynamic human-agent interaction. |
| 10 | 2404.08630 | A Conceptual Framework for Conversational Search and Recommendation: Conceptualizing Agent-Human Interactions During the Conversational Search Process | Develops a conceptual framework of user and agent actions/intents during conversational search, identifying the decision points where the agent steers the dialogue toward a successful or satisfactory conclusion. |

**Deep-read selection rationale:** the four most relevant to the manuscript's core question were chosen — the two empirical human-trust-in-conversational-search studies (2608.21177, 2403.09987), the dynamic trust-modeling study (2404.19291), and the controlled tool-use study that anchors the tool side (2604.03465).

---

## 2. Stored-Library Overlap Note

The local stored paper library was checked against all 10 search results. **The library is currently empty — nothing is stored yet (0 papers).** Therefore **all 10 papers are new**: none had been previously downloaded or stored. The four papers above that were deep-read were fetched from arXiv during this session; the other six are represented at abstract level only.

---

## 3. Glossary Terminology (Chinese agreed terms)

The translation workspace holds **230 glossaries**. The list was reviewed and the four plausible research/agent-related candidates were pulled and inspected individually:

| Glossary name | ID | Applicable? |
|---------------|----|-------------|
| Research Digest Terminology | `gls_0HcAER9gebpqEzSrhnzADW` | Retrieved — **contains no entries** (empty; also not Chinese-specific) |
| MCP Pilot Terms | `gls_03bHFgFBsHuavcxWEVnPj2` | Retrieved — **contains no entries** (empty) |
| MCP Press Terms | `gls_07CNXdAefWzftaYgMWW0hE` | Retrieved — **contains no entries** (empty) |
| MCP Partner Workshop Glossary | `gls_0H58kb4xEhgzllMFxexd5B` | Retrieved — **contains no entries** (empty) |

**Conclusion: there is no applicable Chinese terminology glossary in the workspace.** No glossary with agreed Chinese terms for this manuscript's domain (AI agents, tool use, human trust, conversational search) exists — the four research-adjacent candidates are all empty, and the remaining 226 are unrelated (finance, tourism, product UI, hardware, launch/marketing campaigns in other language pairs, etc.). The Chinese translation below therefore follows standard academic Chinese usage rather than an enforced team glossary. **Recommendation:** if agreed Chinese terminology exists anywhere, it should be imported into a new glossary (e.g., `Agent Trust 中文术语`) before the manuscript text is finalized, so future translations enforce it.

---

## 4. Reading Math (computed precisely)

- **Papers the searches returned:** 10 (5 per search)
- **Deep-read capacity:** 40% of 10, rounded down = **⌊10 × 0.4⌋ = 4 papers**. The full text of these 4 was retrieved in this session (papers #1, #6, #7, #8 above), so their takeaways draw on full text rather than abstracts alone.
- **Section budget:** 1,500-word cap with summaries of ~110 words each = **⌊1500 ÷ 110⌋ = 13 full summaries** that fit in the section (13 × 110 = 1,430 words, leaving 70 words of headroom; a 14th summary would need 1,540 words and would exceed the cap).
- **Implication:** all 10 papers could be summarized as full entries (10 ≤ 13), with room for 3 more papers if additional searches are run later.

---

## 5. 中文版核心结论（Chinese one-paragraph takeaway）

在本节相关工作综述中，我们探讨人们如何对代为搜索并使用工具的人工智能代理赋予信任。本文依托于两次 arXiv 检索所获得的十篇文献——一次检索聚焦于工具使用型智能体，另一次聚焦于人类对对话式搜索智能体的信任——相关文献的研究结果主要集中于三点。第一，用户往往对基于大型语言模型（LLM）的对话式搜索代理（如ChatGPT）的信任度高于对传统搜索引擎的信任度；然而，这种信任较为脆弱，并受以下因素影响：信息来源的可信度、界面模态（文本、语音或具身化）、用户既有知识以及交互方式。其次，信任具有动态性而非静态性：时间序列建模表明，智能体表现的时间先后顺序以及近因效应共同影响着信任在协作过程中的演变。第三，工具的使用本身并不能保证代理的优越性：经过严格控制的实验表明，当工具使用者能力弱于工具合成者时，收益往往集中体现；过于全面的工具反而可能损害泛化能力；此外，工具还蕴含着隐性的算力（token）成本和操作（action）成本。综上所述，这些研究主张将对使用工具的搜索智能体的信任视为一种动态的、受界面中介影响的判断，而非仅由智能体自身所具备的静态属性。

*Note: translated from English to Simplified Chinese (zh-CN) with formal academic tone. No glossary was applied because no applicable Chinese glossary exists in the workspace (see Section 3).*

---

## Appendix — Verification trail

- **Searches:** `tool use agents` → 5 papers; `human trust in conversational search agents` → 5 papers (IDs/titles above are as returned; abstract of 2404.08630 confirmed via direct abstract lookup after a truncated response).
- **Stored library:** `list_papers` returned 0 papers (empty).
- **Glossaries:** 230 glossaries listed; the 4 research-adjacent candidates retrieved individually, all with no entries.
- **Math:** ⌊10 × 0.4⌋ = 4 deep-reads (performed); ⌊1500 / 110⌋ = 13 full summaries fit.
- **Deep-read papers (full text fetched this session):** 2604.03465, 2608.21177, 2403.09987, 2404.19291.
