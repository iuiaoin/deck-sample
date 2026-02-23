**Task**: Create a technical sharing deck that horizontally compares 9 AI coding agent tools, provides use-case guidance and practical experience.
**Slide count**: 15 ± 2
**Language**: Chinese (中文), with English tool names retained
**Audience**: Engineers and technical managers with software development experience
**Goals**:
- Compare and evaluate Claude Code CLI, Codex CLI, Cursor, Windsurf, GitHub Copilot (VS Code), Augment Code, Cline, Devin, and V0
- Explain suitable use cases and tool-selection advice
- Summarize with practical hands-on experience and opinions
**Style**: Restrained, high information density, presentation-friendly. Minimal hype, evidence-based.

---

## Visual & Layout Guidelines

- **Overall tone**: Warm, restrained, professional — inspired by Claude.com aesthetic (see `resources/color_scheme_reference.png`)
- **Background**: `#F7F4EF` (warm beige)
- **Primary text**: `#2B2A27` (deep charcoal)
- **Secondary text**: `#5D4E42` (medium brown)
- **Accent (primary)**: `#E07A59` (coral orange — borders, icons, key data highlights)
- **Accent (secondary)**: `#9FD3B8` (mint green — secondary highlights, status indicators)
- **Typography**: Inter 600-700 for headings (48-72px), Inter 400-500 for body (18-30px), PingFang SC / Microsoft YaHei fallback for Chinese, Source Code Pro for code
- **Per-slide rule**: 1 key point + up to 4 supporting bullets; avoid large blocks of text
- **Footer**: page number (right), section name (left)

---

## Slide-by-Slide Outline

**Slide 1 | Cover**
- Title: AI Coding Agent 工具横评与实战经验
- Subtitle: 九款主流工具的深度对比、场景适配与选型建议
- Footer: 演讲者姓名 · 2026.02
- Visual element: Abstract geometric pattern with tool logos arranged in a subtle grid; warm beige background with coral accent shapes
- Speaker notes: 开场介绍背景——AI coding 是当下最火的方向，工具层出不穷，开发者面临选择困难

**Slide 2 | Agenda**
- 行业全景与赛道分类
- 逐类工具深度分析（AI-Assisted → CLI Agent → End-to-End → Vertical）
- 九工具横向对比矩阵
- 场景适配与选型指南
- 实战经验与思考
- Visual element: Numbered vertical timeline/roadmap layout with coral accent markers
- Speaker notes: 快速过一遍整体结构，让听众知道会覆盖哪些内容

**Slide 3 | 行业全景：AI Coding 赛道细分**
- Key point: AI coding 工具可分为三大赛道，定位和目标用户截然不同
- Supporting:
  - **AI-Assisted Coding**（增强器）：Cursor, GitHub Copilot, Windsurf, Augment Code — 嵌入开发者现有工作流，提升编码效率
  - **End-to-End Agent**（自主执行）：Claude Code, Codex CLI, Cline, Devin — 目标是独立完成开发任务的"初级工程师"
  - **Vertical Vibe Coding**（垂直平台）：V0 — 面向特定场景（前端 UI），以自然语言驱动生成
  - 边界逐渐模糊：Cursor 已推出 Background Agent，Claude Code 可以 pair programming
- Visual element: Three-column card layout with icons; each column represents a category. Use coral/mint/brown color coding for three categories
- Speaker notes: 这三个分类不是绝对的，很多工具在跨界。但理解这个框架有助于后续分析

**Slide 4 | AI-Assisted Coding：Cursor — 野心勃勃的领跑者**
- Key point: Cursor 凭借杀手级 TAB Edit + 先发品牌优势，稳坐 AI Code Editor 头把交椅
- Supporting:
  - 核心优势：TAB Edit（不只是补全，而是"编辑"代码），多处联动修改在重构时极其有用
  - Agent Mode 让非程序员群体先火，建立了"AI 编程 = Cursor"的品牌心智
  - Background Agent / BugBot 信号明确：要和 Devin 硬碰硬，走向全自动
  - 弱点：IDE 本身迭代比 VS Code 慢，Max Mode 额外收 20% margin，定价模式模糊
- Visual element: Feature highlight card with Cursor logo area; key metrics in accent-colored badges
- Speaker notes: Cursor 好在一种组合拳——先用硬核功能抓住核心用户，再乘 Agent 浪潮扩大影响力。如果不知道选什么，Cursor 是个稳的选择

**Slide 5 | AI-Assisted Coding：GitHub Copilot & Windsurf**
- Key point: Copilot 是里程碑式产品但逐渐被超越，Windsurf 被 OpenAI 收购后前途未卜
- Supporting:
  - **GitHub Copilot**：第一个让人感觉"能用"的 AI coding 工具；体验逐渐落后（大厂包袱、资源分散、受限 VS Code 壳）；但 VS Code 最近发力追赶，长远可能重回巅峰
  - **Windsurf**：据说对复杂项目上下文管理更智能；被 OpenAI 收购，看中的可能是 long context 管理能力和用户数据
  - 两者共同困境：在 Agent 时代，AI-assisted coding 的 UX 差异正在被抹平
- Visual element: Two-panel comparison layout (Copilot left, Windsurf right) with feature bullets and status indicators
- Speaker notes: VS Code + Copilot 对于习惯传统 IDE 的开发者仍是不错选择，特别是企业环境。Windsurf 的未来取决于 OpenAI 的整合策略

**Slide 6 | CLI-Based Agent：Claude Code — 不需要 IDE 的 Agent**
- Key point: Claude Code 证明了 Agent 并不需要 IDE，CLI 的可组合性和 prompt 调教水平使其明显"更聪明"
- Supporting:
  - 核心理念：CLI 无限可组合性（第一性原理）；prompt + tool spec 精心调教，体感比 Cursor 更聪明
  - 能力进化：从"聪明"到"持久"——宣称能独立跑 7 小时；体现任务规划、自我反思行为
  - 成本优势：Pro Plan $20 即可使用，LLM 原厂的闲时资源优势（API 计费同等任务可能 $10+）
  - 生态扩展：GitHub 上 @claude-code 自动干活（CI 集成），断供 Windsurf 表明战略决心
- Visual element: Terminal-style code block showing Claude Code interaction example; key stats in accent badges
- Speaker notes: Claude Code 给人一种"确实应该能 work"的感觉。如果你习惯终端工作流，这是目前体验最好的 CLI agent

**Slide 7 | CLI-Based Agent：Codex CLI & Cline**
- Key point: Codex CLI 是 OpenAI 的 Agent 入口布局，Cline 代表开源 BYOK 路线的价值
- Supporting:
  - **Codex CLI**：通过 ChatGPT 派活（手机也行），真正的全自动体验；OpenAI 野心不止 coding——ChatGPT 要成为调度入口乃至操作系统
  - **Cline**：开源、全链路透明、本地运行；BYOK（Bring Your Own Key）模式，完整上下文不压缩；对企业数据安全友好
  - 共同趋势：CLI/终端 agent 正在证明 IDE 并非 agent 的必要载体
- Visual element: Two-panel layout with terminal icons; Codex CLI (closed-source badge) vs Cline (open-source badge)
- Speaker notes: Codex CLI 的意义在于 OpenAI 生态整合。Cline 则是对不想被厂商锁定的团队的理想选择

**Slide 8 | IDE 深度集成：Augment Code — 全仓库理解**
- Key point: Augment Code 主打全仓库级别的代码理解，适合大型 monorepo 和企业级代码库
- Supporting:
  - 核心差异：全仓库嵌入（embedding）预构建知识库，模型回答时如同有"代码百科"可查
  - 适用场景：大型代码库（60万+ 行）、monorepo、需要跨文件/跨模块理解的复杂任务
  - 定位：不是通用 AI IDE，而是深度上下文增强层，可与现有 IDE 配合
  - 局限：对小项目优势不明显，依赖预处理步骤
- Visual element: Layered architecture diagram showing codebase → embedding → knowledge base → AI response pipeline
- Speaker notes: 如果你的项目是大型 monorepo（类似 RisingWave 60万行 Rust），Augment Code 的全仓库理解能力值得关注

**Slide 9 | End-to-End 自主执行：Devin — 全自动"初级工程师"**
- Key point: Devin 是全自动 Agent 的先行者，产品完成度高但面临 Cursor/Claude Code 的多面夹击
- Supporting:
  - 优势：Integration 最强（Slack/Linear/Jira 直接派活）、Knowledge Base & Playbook 系统完善、Confidence Rating 避免盲目烧钱
  - 代价：Agent 非常烧钱（一个 issue 轻松 $5-10+，加 vCPU 成本）；模型智力水平一般，复杂 bug 容易乱撞
  - 最佳用法：先让 Devin 生成初版，再用 Cursor/Claude Code 精修（"treat Devin like a junior engineer"）
  - 竞争压力：Cursor Background Agent + Claude Code CI 模式正在侵蚀 Devin 的地盘
- Visual element: Workflow diagram: User assigns task → Devin explores → generates draft → human reviews. Cost badge showing $/task range
- Speaker notes: Devin 的 integration 和产品设计是值得学习的，但全自动 agent 目前仍是"半成品"，需要合理预期管理

**Slide 10 | 垂直平台：V0 — 前端 UI 的 Vibe Coding**
- Key point: V0 是垂直赛道中做得最有品味的产品，利用 React/shadcn 组件化能力实现"自然语言驱动的 Figma"
- Supporting:
  - 核心体验：用自然语言"画"界面，生成的组件可直接整合到代码项目中
  - Vercel 基因：前端领域深厚积累 + 自研模型（专注 web 应用错误修复和快速编辑）
  - 扩展野心：从 UI prototype 走向 "Full stack vibe coding platform"，GitHub sync 打通现有代码
  - 局限：高度依赖 React/Next.js 生态，复杂后端逻辑仍需其他工具
- Visual element: Side-by-side layout: natural language prompt (left) → generated UI preview (right), with Vercel/shadcn logos
- Speaker notes: V0 适合快速出前端 prototype，特别是 React/Next.js 项目。但不要期望它处理复杂后端逻辑

**Slide 11 | 横向对比矩阵**
- Key point: 九款工具在核心维度上各有侧重，没有"全能冠军"
- Visual element: Feature comparison table (9 columns × ~8 rows):
  - 行维度：工具形态、主要模型、自主执行能力、上下文管理、成本模型、开源/闭源、IDE 依赖、最佳场景
  - 列：Claude Code | Codex CLI | Cursor | Windsurf | Copilot | Augment | Cline | Devin | V0
  - 使用 coral/mint 色块标注优势/劣势
- Speaker notes: 这张表不是排名，而是帮助大家根据自己的需求找到最匹配的工具。注意关注你最在意的维度

**Slide 12 | 场景适配：什么场景用什么工具？**
- Key point: 选工具的关键不是"哪个最强"，而是"哪个最适合你的场景"
- Supporting:
  - **日常编码增效**：Cursor（综合最稳）/ Copilot（企业环境、VS Code 偏好）
  - **独立完成开发任务**：Claude Code（CLI 偏好、性价比高）/ Devin（需要 integration、可接受成本）
  - **大型代码库理解**：Augment Code（monorepo）/ Cursor Max Mode
  - **前端快速原型**：V0（React 生态）
  - **开源/数据安全优先**：Cline（BYOK、本地运行）
  - **探索性/低门槛**：Codex CLI（ChatGPT 生态、手机可派活）
- Visual element: Scenario-to-tool mapping grid; each scenario is a card with recommended tool(s) highlighted in coral
- Speaker notes: 选工具要考虑：团队技术栈、安全要求、预算、项目复杂度。没有银弹，多试才能找到最适合的

**Slide 13 | 实战经验与踩坑总结**
- Key point: Agent 是一门"手艺"——效果极度依赖使用者的 prompt 能力和对工具的理解
- Supporting:
  - Agent 仍是"半成品"：加功能很爽，但微调按钮位置/布局/交互时往往改不对
  - 成本意识很重要：一个任务 $5-10 是常态，"穷人思维"反而限制了探索；但盲目跑也会烧钱
  - 最佳实践：先让 Agent 生成初版 → 人工/Cursor 精修；写好 AGENT.md/Cursor Rules；在团队内积累 prompt 技巧和知识库
  - 关键心态转变：把 Agent 当外包/初级工程师，派活 → 检查 → 给反馈，而非期望一次性搞定
- Visual element: Three insight cards with icons (craft/cost/workflow), each containing 1-2 bullet points
- Speaker notes: 了解 AI 能力边界 + prompt engineering 是用好 agent 的关键。Agent 可能是越用越好用的东西，需要持续投入

**Slide 14 | 未来趋势与行业走向**
- Key point: Agent 能力从"聪明"走向"持久"，行业格局远未定型
- Supporting:
  - 趋势一：从 AI-assisted → 全自动 Agent（半自动到全自动是明确方向）
  - 趋势二：IDE 与 CLI 双轨并行；Cursor 要做 All-in-one 入口，CLI agent 证明 IDE 非必须
  - 趋势三：成本仍是最大瓶颈；LLM 降价将重塑格局，原厂做 agent 有成本优势
  - 趋势四：壁垒的本质是"快"——在这个发展过快的领域，任何技术领先都可能被迅速追赶
- Visual element: Trend arrows or timeline showing evolution: Autocomplete → Chat → Agent Mode → Background Agent → Fully Autonomous
- Speaker notes: 未来 1-2 年会是关键窗口期。对开发者来说，现在就开始积累 agent 使用经验是一种投资

**Slide 15 | 总结与建议**
- Key point: 拥抱变化、审慎实践，让 AI Agent 成为你的得力"副驾"
- Supporting:
  - 立即行动：从你最常用的场景开始试用 1-2 个工具，不必等到"完美"
  - 保持审慎：始终 review AI 产出，人类是最终负责人
  - 团队共建：在团队内分享经验、积累 prompt 和知识库，形成正向循环
  - 关注本质：工具会更迭，但"清晰表达需求 + 审查 AI 输出"的能力是持久的
- Visual element: Four-quadrant summary card with icons for each recommendation; closing statement in accent color
- Footer: 谢谢 · Q&A
- Speaker notes: 多说无益，最好的方式还是自己上手试。保持开放心态，同时不要被 hype 裹挟

---

## Content & Tone Guidelines

- **信息密度优先**：每页 slide 要有实质内容，避免空洞的概括性语句
- **克制风格**：不用过度渲染词汇（如"颠覆""革命"），用事实和对比说话
- **个人观点标注**：涉及主观判断时，明确标注"个人观点"或"基于实践经验"
- **平衡呈现**：每个工具既讲优势也讲局限，避免偏向任何一个工具
- **实用导向**：听众听完后应该能回答"我应该先试哪个工具"
- **中文为主**：正文使用中文，工具名称、技术术语保留英文

---

## Data Sources & References

- `resources/我对各种AICoding Agent工具的看法.md` — 主要来源：Cursor、Copilot、Claude Code、Codex CLI、Devin、V0 的详细分析和个人观点 → 映射到 Slides 4-10, 13
- `resources/行业格局与技术趋势.md` — 行业格局概览、技术趋势分析、Augment Code 和 Cline 的定位 → 映射到 Slides 3, 7, 8, 14
- `resources/作为开发者的应对建议.md` — 开发者建议、团队实践、安全考量 → 映射到 Slides 12, 13, 15
- `resources/未来展望:AI 编程智能体的进化方向.md` — 未来趋势、人机协作范式 → 映射到 Slide 14
- `resources/学术前沿探索.md` — 学术背景参考（SWE-Agent, AgentCoder 等）→ 作为 Slide 14 的技术支撑
- `resources/AI 编程智能体工具调研报告.pdf` — 综合调研数据 → 补充各 slide 的细节
- `resources/color_scheme_reference.png` — Claude.com 风格参考 → 映射到视觉设计规范

---

## Deliverables

- Output: 15 HTML slides in `presentation/slides/`
- Viewer: `presentation/index.html` (from viewer template)
- Each slide: standalone HTML, 1280x720, 16:9 aspect ratio
- Optional: `PRESENTATION_SUMMARY.md`, `PRESENTATION_SCRIPT.md`
