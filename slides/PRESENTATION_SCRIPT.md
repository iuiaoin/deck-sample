# Speaker Notes

## Slide 1 — Cover
开场介绍背景：AI coding 是当下最火也最卷的方向，工具层出不穷，隔三差五就有新工具、新功能发布。很多开发者面临选择困难，甚至有人连 Cursor 都没用过。今天我们来做一个系统性的横向对比。

## Slide 2 — Agenda
快速过一遍整体结构。我们会先建立一个分类框架，然后逐类分析九款工具，做一个全维度对比，给出场景选型建议，最后分享实战中的真实经验和思考。

## Slide 3 — 行业全景
这三个分类不是绝对的，很多工具已经在跨界。比如 Cursor 推了 Background Agent，Claude Code 也能 pair programming。但理解这个框架有助于我们后续的分析——不同赛道解决的核心问题不同。

## Slide 4 — Cursor
Cursor 好在一种组合拳：先用 TAB Edit 这个杀手级功能抓住最挑剔的核心用户，然后乘着 Agent 浪潮在大众心中建立了"AI 编程 = Cursor"的品牌认知。它不一定是技术最强的，但综合来看是目前最稳的选择。$9B 估值说明资本也在押注这个方向。

## Slide 5 — Copilot & Windsurf
Copilot 是里程碑式产品，但大厂包袱让它逐渐被超越。好消息是 VS Code 最近在认真追赶。Windsurf 被 OpenAI 收购后前途未卜，但它在 long context 管理上的积累可能会赋能 OpenAI 的模型。对企业环境来说，Copilot 仍是最安全的选择。

## Slide 6 — Claude Code
Claude Code 给人一种"确实应该能 work"的感觉。它的 prompt 和 tool spec 写得非常精心，体感比 Cursor 的 agent 更聪明。Pro Plan $20 即可使用，相比 API 计费有巨大的成本优势——这就是 LLM 原厂做 agent 的好处，闲时资源可以充分利用。

## Slide 7 — Codex CLI & Cline
Codex CLI 的意义在于 OpenAI 生态整合——通过 ChatGPT 派活，手机也能用。Cline 则代表了开源 BYOK 路线：代码不离开本地、模型可自选、全链路透明。对数据安全要求高的团队，Cline 是理想选择。

## Slide 8 — Augment Code
如果你的项目是大型 monorepo，Augment Code 的全仓库理解能力值得关注。它通过 embedding 预构建知识库，能回答"xxx 是怎么 work 的"这类模糊问题，这是普通 agent 用 grep 做不到的。但对小项目优势不明显。

## Slide 9 — Devin
Devin 的 integration 和产品设计是值得学习的，但全自动 agent 目前仍是"半成品"。烧钱是真的——一个 issue 轻松 $5-10+。官方建议"treat Devin like a junior engineer"，这其实适用于所有 Agent 产品。最佳用法是生成初版再精修。

## Slide 10 — V0
V0 适合快速出前端 prototype，特别是 React/Next.js 项目。Vercel 的前端积累加上自研模型，让这个垂直赛道的体验做得非常好。但不要期望它处理复杂后端逻辑。它正在从 UI prototype 走向全栈平台。

## Slide 11 — 横向对比矩阵
这张表不是排名，而是帮助大家根据自己最在意的维度找到最匹配的工具。注意看最后一行"最佳场景"——没有全能冠军，每个工具都有自己的甜蜜点。

## Slide 12 — 场景适配
选工具的四个关键因素：团队技术栈、安全合规要求、预算、项目复杂度。没有银弹，建议从自己最常用的场景开始，试用 1-2 个工具，积累实际经验后再决定。

## Slide 13 — 实战经验
三个核心洞察：一是 Agent 是一门"手艺"，效果极度依赖使用者的能力；二是成本意识很重要但不要被"穷人思维"限制探索；三是心态转变——把 Agent 当初级工程师来管理，迭代式协作效果最好。

## Slide 14 — 未来趋势
从 Autocomplete 到 Fully Autonomous，进化方向很清晰。四个趋势：半自动到全自动、IDE 与 CLI 双轨并行、成本是最大瓶颈、壁垒的本质是"快"。未来 1-2 年是关键窗口期，现在积累 agent 使用经验是一种投资。

## Slide 15 — 总结
四个建议：立即行动、保持审慎、团队共建、关注本质。工具会不断更迭，但"清晰表达需求 + 审查 AI 输出"的能力是持久的。多说无益，最好的方式还是自己上手试。
