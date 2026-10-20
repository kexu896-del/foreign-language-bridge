# 外语桥（foreign-language-bridge）

口语与听力陪练技能（英语为主），面向想把英语作为工作语言、同时保留日常交流的职场人士。

## 结构

```
foreign-language-bridge/
├── SKILL.md
└── references/
    ├── basic-training-plan.md       # 四周基础计划、纯文字/无语音路径
    ├── w1-demo-pack.md              # W1 全流程示范（合成）
    ├── session-design.md            # 时长/难度/辅助模式、预习卡、覆盖率台账
    ├── target-language-inventory.md # 功能-情景目标清单
    ├── rubric-anchors.md            # 六维评分锚点与校准
    ├── coaching-protocol.md         # 陪练协议与缺口双轨
    ├── diagnostic-and-evidence.md   # 三种基线、听众复述、延迟复测、证据卡
    ├── scenarios.md                 # 12 个工作/日常情景卡
    ├── session-log-and-cards.md     # 日志、收口报告、Anki 卡片
    ├── listening-loop.md            # 听力任务、错误分层、支架与 14 天循环
    ├── listening-sources.md         # 听力材料与发音音频来源
    ├── rubric-speaking-review.md    # 口语复盘标准（v1 草稿）
    ├── pronunciation-self-practice.md # 可选发音自练
    ├── host-integration-kimi.md     # Kimi 语音接入与同会话验证
    └── skill-borrowing.md           # 外部来源与许可说明
```

## 使用

1. 在支持技能安装的宿主中安装本目录（如 OpenCode 全局技能目录或 Kimi 的技能管理）。
2. 首次按 `references/basic-training-plan.md` 做 30 分钟准备（测麦、隐私、基线、选情景）。
3. 每次练习：说主题/时长/难度/模式 → 看预习卡 → 说 **“I'm ready.”** → 角色扮演 → 说 **“Let's wrap up.”** 收报告。
4. 按日志与卡片复习；7 天做平行任务，30 天做一次真实任务复测。
5. 语音路线见 `references/host-integration-kimi.md`；纯文字路线见 `basic-training-plan.md`。

## 边界

- 不评估/认证发音、流利度、实时听力；相关结论只能来自宿主、外部测评或真人。
- 不替代真实会议与谈判经验；不构成法律、医疗或心理建议。
- 录音/转写需同意与脱敏；不投喂客户或原单位材料。

## 状态

v0.5.1（testing）。结构自检：`node tests/check-package.mjs`；OpenCode/Kimi 运行时触发、语音通话与转写组合待实测。
