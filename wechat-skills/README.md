# WeChat Official Account Skills

这是一组面向微信公众号写作的 Codex skill 草案，适合按需拆开使用，而不是把所有写作动作都塞进一个 skill 里。

包含的 skill：

1. `wechat-topic-planner`
   用于选题策划、角度拆分、栏目化选题池生成。
2. `wechat-title-hook-generator`
   用于标题、开头、摘要、封面文案生成。
3. `wechat-article-architect`
   用于把素材、观点或提纲扩成适合公众号的长文结构。
4. `wechat-style-polisher`
   用于改稿、润色、重写、增强节奏与可读性。
5. `wechat-series-operator`
   用于做系列选题、栏目运营、连载规划和更新节奏设计。

建议用法：

- 如果用户说“帮我想选题”“做 10 个公众号选题”，优先触发 `wechat-topic-planner`
- 如果用户说“给我起标题”“帮我写开头”，优先触发 `wechat-title-hook-generator`
- 如果用户说“根据这些素材写成公众号文章”，优先触发 `wechat-article-architect`
- 如果用户说“帮我改稿”“按公众号风格润一下”，优先触发 `wechat-style-polisher`
- 如果用户说“帮我规划一个月栏目”“做个连载”，优先触发 `wechat-series-operator`

如果你希望，我下一步还可以继续把这套 skill：

- 合并成一个总控 skill
- 改成你的个人文风版本
- 搬到真正的 Codex skills 目录并补充示例模板
