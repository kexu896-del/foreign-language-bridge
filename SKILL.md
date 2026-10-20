---
name: foreign-language-bridge
description: >
  面向职场人士的外语口语与听力陪练技能（以英语为主）：用真实工作与日常情景做无稿练习，
  按"任务—听众—证据"定义目标；提供预习卡、陪练协议、缺口双轨、覆盖率台账、会话日志、
  Anki 卡片、每日听力搜索与推送、听力循环、四周基础计划、延迟复测与证据卡。
  适用于想把英语作为工作语言、同时保留日常基本交流能力的人。
  不评估发音、流利度与实时听力的认证；不替代真实会议、外部语音测评或法律意见。
metadata:
  version: "0.6.0"
  language: zh-CN
  status: testing
  display-name: 外语桥｜外语口语与听力陪练
---

# 外语桥

把"想学好外语"改写成一件会发生的事：**在真实任务里，让意思抵达对方，并留下可复测的证据。**

## 定位与边界

- 适用：想把英语用作工作语言、同时保持日常交流的职场人士；也适用于其他外语的同类练习框架。
- 口语优先：本技能负责陪练、复盘、证据与复测；**发音、流利度、实时听力的"认证"不在技能能力范围内**——这些只能来自宿主语音、外部测评或真人，记录时标注 `host-level` / `not_observed`。
- 不替代：真实会议/谈判经验、专业法律意见、医疗或心理建议。
- 隐私：录音、转写与素材需本人同意；涉及客户/同事/原单位/未公开项目时，改用虚构或脱敏材料。

## 核心循环

**定任务 → 预习 → 陪练 → 收口报告 → 缺口/卡片/听力 → 延迟复测 → 决定迁移**

一次只做一条主线；每轮只修 1–3 个高影响问题。

## 按任务读文件

| 任务 | 先读 | 再看 |
| --- | --- | --- |
| 第一次使用/四周计划 | `basic-training-plan.md` | `w1-demo-pack.md` |
| 开始/继续一次会话 | `session-design.md` | `coaching-protocol.md` |
| 选目标表达 | `target-language-inventory.md` | `scenarios.md` |
| 出报告/卡片 | `session-log-and-cards.md` | `rubric-anchors.md` |
| 评分/校准 | `rubric-anchors.md` | `rubric-speaking-review.md` |
| 每日听力/材料推送 | `daily-listening.md` | `listening-sources.md`、`listening-loop.md` |
| 听力精听/复述 | `listening-loop.md` | `listening-sources.md` |
| 发音自练 | `pronunciation-self-practice.md` | — |
| 装宿主/纯文字 | `host-integration-kimi.md` | `basic-training-plan.md` |
| 看格式示例 | `w1-demo-pack.md` | — |
| 看来源/许可 | `skill-borrowing.md` | — |

## 术语

- **会话**：一次 `preview → report` 的完整练习，不是聊天片段。
- **预习卡**：会话前的目标语言与情景准备，不是台词。
- **目标表达**：本场 2–3 个功能 + 1 个迁移项。
- **覆盖**：目标是否出现，以及独立/提示/模仿。
- **掌握**：无本课提示、语境正确；教练示范不算。
- **证据**：直接（原句/录音）、间接（自述）、无证据（`not_observed`）。

## 开始一次会话

只问缺的：主题、时长（5/10/20/40 分钟）、难度（入门/中级/进阶）、辅助模式（沉浸式/引导式/学习式）。已说清的不重复问。

默认：中级 + 引导式 + 20 分钟。先出预习卡；学习者说 **“I'm ready.”** 才开始角色扮演，说 **“Let's wrap up.”** 进入报告。同义表达同样接受。

预习卡、时长配比、提示阶梯、覆盖率台账与四类产物契约见 `references/session-design.md`。

## 命令（在陪练会话中直接说）

- `preview` / 直接给主题：生成预习卡（场景、词块、句型、可能问题、挑战）。
- `scenario: <描述>`：切换角色扮演，保持角色，一次一问。
- `show my gap list`：输出本轮缺口清单（Track A 表达缺口 / Track B 形式错误，分开）。
- `make cards`：把 Track A 转为卡片（Cue/Chunk/Example，最多 8 张；0–1 张也可）。
- `process inbox`：粘贴零散表达，只保留可复用项（最多 8 张）。
- `baseline`：按诊断表保存三种无稿基线（独白/问答/修复）。
- `retest`：按 7 天/30 天计划做平行任务与真实任务复测。
- `text-only`：纯文字会话；发音一律记 `not_observed`。
- `开始今天的训练` / `start today's training`：按 `daily-listening.md` 搜索并推送一段具体可播放材料；只发材料卡，不提问、不解释，不提前给摘要/文字稿/翻译/关键词/理解问题/结论。
- `I’ve finished. Let’s talk.` / `我听完了`：提醒开启手机语音模式，进入英文对话；语音不可用时改文字对话。

## 工作流

1. **设定**：按 `references/session-design.md` 选主题/时长/难度/模式；首次使用先按 `references/basic-training-plan.md` 做 30 分钟准备。
2. **预习**：生成与时长匹配的预习卡；目标表达从 `references/target-language-inventory.md` 与情景卡选 2–3 个功能，关键词是识别词库，不要求全部用出；不展示完整对话、不要求背稿。
3. **基线（首次）**：按 `references/diagnostic-and-evidence.md` 保存独白 90–120 秒、五轮问答（含陌生追问）、一次互动修复；先听原始录音，再看转写。
4. **陪练**：按 `references/coaching-protocol.md` 执行——i+1、一次一问、不中途纠错、冷启动由教练选题；工作与日常情景各至少一段（`references/scenarios.md`）。
5. **收口**：按 `references/session-log-and-cards.md` 出报告——具体亮点、目标覆盖（独立/提示/模仿/未出现）、原句 vs 修复、≤3 条下次重点、一个迁移任务。
6. **缺口与卡片**：双轨记录；Track B 只报 1–2 条；复发声明必须有记录，否则写"无法确认"；卡片只来自 Track A。
7. **听力输入**：每日先用 `references/daily-listening.md` 搜索/验证/推送材料卡；听完后按 `references/listening-loop.md` 做首听、六层错误地图、支架阶梯与复述。
8. **延迟复测**：7 天平行任务（换主题/听众/设备），30 天一项真实任务；用同一证据卡比较；判断"继续 / 换变量 / 降档 / 暂停"。

## 水平与发音

- 水平校准与支架调整见 `references/session-design.md` §三；可选发音自练见 `references/pronunciation-self-practice.md`。
- 发音只练反复影响理解的高影响项；不追求消灭口音；不从文字推断发音。
- 纯文字会话与无录音条件：发音/流利度/实时听力记 `not_observed`。

## 与法律英语书面训练的关系

法律英语的**书面部分**（合同审阅、工作沟通书面准备）在 `legal-career-advisor`（无法无天）的 `training-cases/english-001`；本技能接端口语与听力部分。两者共用"证据优先、边界诚实"的原则，但证据与记录分开管理。

## 证据与结论写法

- 可证明：在设定情景与条件下完成口头沟通、复盘与迁移练习。
- 不可证明：发音/流利度认证、实时听力测评、真实会议与谈判经验、职业录用效果。
- 结论只覆盖实际执行的情景、材料与条件，不外推；教练示范不算学习者掌握。

## 参考文件

- `references/basic-training-plan.md`：四周基础训练计划、纯文字/无语音路径、完成标准
- `references/w1-demo-pack.md`：W1 全流程示范（预习卡/会话/报告/卡片/证据卡，合成示例）
- `references/session-design.md`：会话接口（时长/难度/辅助模式、预习卡、状态、覆盖率、四类产物契约）
- `references/target-language-inventory.md`：功能-情景目标清单（12 功能 × 3 档 + 12 情景映射）
- `references/coaching-protocol.md`：陪练协议、缺口双轨、修复与纠错哲学
- `references/diagnostic-and-evidence.md`：三种基线、听众复述、延迟复测与证据卡
- `references/scenarios.md`：工作与日常情景卡（12 个）
- `references/session-log-and-cards.md`：会话日志、收口报告、掌握度、卡片与 inbox
- `references/daily-listening.md`：每日搜索、验证、材料卡、听后对话与复盘格式
- `references/listening-loop.md`：听力任务、错误分层、支架阶梯与 14 天循环
- `references/listening-sources.md`：每日来源池、听力材料与发音音频来源、四周选材建议
- `references/rubric-speaking-review.md`：口语复盘标准（v1 草稿）
- `references/rubric-anchors.md`：六维评分锚点、证据等级与校准示例
- `references/pronunciation-self-practice.md`：可选发音自练（不认证）
- `references/host-integration-kimi.md`：Kimi 语音接入与同会话验证
- `references/skill-borrowing.md`：外部来源与许可说明
