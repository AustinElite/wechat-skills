# WeChat Writing Skills for Codex

一套面向 **微信公众号写作** 的 Codex skills，帮助你把公众号内容工作流拆成可复用、可组合的能力模块。

这套仓库适合下面几类场景：

- 想给 Codex 增加公众号写作能力
- 想把“选题、标题、成稿、改稿、连载运营”拆成独立 skill
- 想沉淀个人内容方法论，并持续迭代
- 想把自己的公众号写作流程产品化、团队化

## 项目特点

- **按写作流程拆分**：不是一个“大而全”的 skill，而是多个专职 skill 协同
- **适合微信公众号场景**：强调标题、开头、结构、节奏、栏目化，而不是泛化内容生成
- **方便二次改造**：可以继续改造成你的个人文风版本、行业版本、品牌版本
- **适合上传 GitHub**：目录清晰，便于展示、协作和后续扩展

## 当前包含的 Skills

### 1. `wechat-topic-planner`
用于公众号选题策划、切入角度拆分、选题池生成和栏目方向设计。

适合场景：

- “帮我想 10 个公众号选题”
- “这个热点可以怎么写”
- “围绕 AI / 职场 / 商业做一组栏目内容”

文件位置：
[wechat-skills/wechat-topic-planner/SKILL.md](E:\Codex\wechat-skills\wechat-topic-planner\SKILL.md)

### 2. `wechat-title-hook-generator`
用于生成标题、开头、摘要、封面短句和转发文案。

适合场景：

- “帮我起标题”
- “这个标题不够抓人，重写一下”
- “帮我写一个适合公众号的开头”

文件位置：
[wechat-skills/wechat-title-hook-generator/SKILL.md](E:\Codex\wechat-skills\wechat-title-hook-generator\SKILL.md)

### 3. `wechat-article-architect`
用于把素材、采访纪要、观点、提纲、新闻链接或语音转文字整理成可发布的公众号长文。

适合场景：

- “把这些素材写成公众号文章”
- “根据这份提纲扩写成一篇长文”
- “按公众号风格整理成稿”

文件位置：
[wechat-skills/wechat-article-architect/SKILL.md](E:\Codex\wechat-skills\wechat-article-architect\SKILL.md)

### 4. `wechat-style-polisher`
用于润色、改稿、重写、精简、扩写与风格统一。

适合场景：

- “帮我润色一下”
- “保留原意，但改得更像公众号”
- “这篇太干了，顺一顺”

文件位置：
[wechat-skills/wechat-style-polisher/SKILL.md](E:\Codex\wechat-skills\wechat-style-polisher\SKILL.md)

### 5. `wechat-series-operator`
用于公众号栏目设计、系列专题规划、内容矩阵搭建和月度排期建议。

适合场景：

- “帮我规划一个月的公众号选题”
- “我想做系列连载，怎么设计”
- “栏目怎么分才更容易持续更新”

文件位置：
[wechat-skills/wechat-series-operator/SKILL.md](E:\Codex\wechat-skills\wechat-series-operator\SKILL.md)

## 目录结构

```text
.
├─ README.md
└─ wechat-skills
   ├─ README.md
   ├─ wechat-topic-planner
   │  └─ SKILL.md
   ├─ wechat-title-hook-generator
   │  └─ SKILL.md
   ├─ wechat-article-architect
   │  └─ SKILL.md
   ├─ wechat-style-polisher
   │  └─ SKILL.md
   └─ wechat-series-operator
      └─ SKILL.md
```

## 如何使用

### 方式一：作为灵感仓库直接参考
你可以直接阅读各个 `SKILL.md`，把其中的结构、流程和约束迁移到你自己的 Codex skill 体系里。

### 方式二：按需复制到你的 Codex skills 目录
如果你已经在本地使用 Codex skill 机制，可以把对应 skill 文件夹复制到你的 skill 目录，再按自己的账号定位继续改写。

建议先改这几类信息：

- 你的账号定位
- 你的典型读者
- 你偏好的语言风格
- 你常写的主题范围
- 你是否更重视传播、转化、深度或个人表达

### 方式三：组合使用
推荐把这些 skill 串成一个完整工作流：

1. 用 `wechat-topic-planner` 做选题
2. 用 `wechat-title-hook-generator` 产出标题和开头
3. 用 `wechat-article-architect` 组织成长文初稿
4. 用 `wechat-style-polisher` 做最终改稿
5. 用 `wechat-series-operator` 规划长期栏目和排期

## 适合继续扩展的方向

你可以基于这个仓库继续新增更多公众号场景 skill，例如：

- 爆款标题实验版
- 采访稿转公众号文章
- 商业观察类公众号写作
- 创始人 IP 口吻写作
- 女性成长 / AI / 职场 / 教育等垂类版本
- 评论区互动与留言引导文案生成
- 配图建议与封面文案协同 skill
