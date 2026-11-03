# Grok Bot 技能模板库

拿来就能用的 Grok Bot 技能（Skill）模板，都是我自己日常在用、改过几轮的版本，去掉了个人信息。

配套内容：
- 手册：[Grok Bot 入门手册](https://github.com/bianwuwei/grok-bot-getting-started)，第 06 章讲 Skill 是什么、什么时候该存。
- 视频课：公众号「無為聊AI」合集 [無為的 Grok Bot 入门课（13 节视频）](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxNzMwMTAxOA==&action=getalbum&album_id=4728796787082575881&scene=305#wechat_redirect)，第 8 课讲存成技能。

## 有哪些

| 技能 | 什么时候用 | 交回什么 |
| --- | --- | --- |
| [weekly-report](skills/weekly-report/SKILL.md) | 有一周的流水账、日志或零散记录，要一份短周报 | 三段式周报：做成了什么、卡在谁、下周谁做什么，外加一行「要我拍板」 |
| [weekly-report-pipeline](skills/weekly-report-pipeline/SKILL.md) | 让大总管一条龙出「行动卡 + 周报」并验收 | 专岗出行动卡，大总管写周报、验收，最后四段回报 |
| [meeting-to-action-card](skills/meeting-to-action-card/SKILL.md) | 有一份会议原始记录，要整理成纪要或某个组的行动卡 | 决定、待办、未决三类，每条带原话出处 |
| [wechat-xiaolvshu-daily](skills/wechat-xiaolvshu-daily/SKILL.md) | 每天要出一条公众号小绿书（贴图消息） | 3 个选题让你挑，再出标题和 1000 字内正文 |

这几个技能有几条共同的规矩：只用原文里有的信息，缺的标「待确认」不去猜；原文件只读不改；发给任何人之前先问你。

## 怎么用

1. 点开一个技能的 `SKILL.md`，把全文复制下来。
2. 在 Grok Bot 的对话里说：「把下面这段存成一个技能」，再贴上全文。
3. 存好后，碰到对应的活，直接说「用 weekly-report 帮我写这周的周报」就行。
4. 想改成你的习惯（条数、格式、受众），直接在对话里让 Bot 改技能，改完拿一份真材料试一遍。

`weekly-report-pipeline` 要先有一个大总管和一个行动卡专岗，并且两者在同一个群里（手册第 04、05 章）。

## 说明

- 基于 2026 年 10 月版本的 Grok Bot 整理，界面和能力可能更新。
- 这是我个人整理的模板，不是 Grok Bot 产品方出品。
- 欢迎提 Issue 说哪里不好用，或者 PR 你自己的技能。

## License

[MIT](LICENSE) © 無為 (bianwuwei)
