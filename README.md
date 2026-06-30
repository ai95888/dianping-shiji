---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: c7010ec7adc9432b135ea39104778c53_fc807e31747c11f1b2f55254006c9bbf
    ReservedCode1: SZgmlN2jR8NCD5Sq0c+o52ySeBbZvXK+lxfYIJu4TSINP6L+jZ6JbHNCamQmj7gUB3oorCV6oIZqJz8xM8X38zOB8Hk5Kzbsc5jZMrHWj2aXteaysbvEdoBuU7aNyKDnqfZ4Hwdxmfj9PjLxkQCXugOZgQv5/anQfGxEd8yYiqHqQKtPC+LeEOqumjE=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: c7010ec7adc9432b135ea39104778c53_fc807e31747c11f1b2f55254006c9bbf
    ReservedCode2: SZgmlN2jR8NCD5Sq0c+o52ySeBbZvXK+lxfYIJu4TSINP6L+jZ6JbHNCamQmj7gUB3oorCV6oIZqJz8xM8X38zOB8Hk5Kzbsc5jZMrHWj2aXteaysbvEdoBuU7aNyKDnqfZ4Hwdxmfj9PjLxkQCXugOZgQv5/anQfGxEd8yYiqHqQKtPC+LeEOqumjE=
---



# 大众点评食记写作 Skill——dianping-shiji

> 只需一个店名，生成真实不AI的大众点评食记。不用刷评价，也能写出让人想去吃的探店笔记。

[![Version](https://img.shields.io/badge/version-3.0-blue)](./SKILL.md)
[![License](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-green)](./LICENSE)
[![Platform](https://img.shields.io/badge/platform-SkillScope%20%7C%20GitHub-orange)](https://skillscope.cn)

---

## 这是什么？

一个给 AI Agent 用的写作技能包。输入一个店名，自动搜索真实评论信息，生成 500-700 字的大众点评风格食记。

**核心理念**：去AI化、真实白话、SEO友好、读起来像饭搭子酒后聊天。

## 解决什么问题？

- **商家**：不敢刷评价（大众点评半年封了5万个账号），但需要真实高质量的食记来吸引顾客
- **美食博主**：一天探店3家的节奏，写稿速度跟不上出片速度
- **本地生活运营**：多个门店需要差异化内容，手动写费时且风格难以统一

## 它怎么做到的？

七大写作引擎驱动：

| 引擎 | 做什么 | 解决什么 |
|------|--------|----------|
| 引擎1：开头钩子 | 三种钩子（场景痛点/反常识/感官暴击） | 开篇3秒吸引，不被划走 |
| 引擎2：五感颗粒度 | 每道菜写视觉+嗅觉+触感+味觉+听觉 | 让读者"闻到""看到""想象出" |
| 引擎3：饭搭子人设 | 聊天体+小槽点+互动钩子 | 去AI味，不像是AI生成的 |
| 引擎4：环境空间叙事 | 门面→抓人细节→服务瞬间三层结构 | 环境不是"装修不错"，而是具体到墙上那幅画 |
| 引擎5：反差记忆点 | 挖掘环境vs价格/预期vs实际等反差 | 让食记不被忘记 |
| 🔥 引擎6：标题工厂（v3.0） | 6种标题模板+推荐指数 | 标题决定打开率 |
| 🔥 引擎7：类型适配（v3.0） | 5类店铺差异化参数表 | 高端店不像路边摊，甜品店不像正餐 |

## 快速开始

### 安装

**方式一：SkillScope（推荐）**

```bash
pip install skillscope
skillscope install dianping-shiji
```

**方式二：GitHub**

```bash
git clone https://github.com/yourusername/dianping-shiji.git
```

### 使用

把 `SKILL.md` 文件放入你的 AI Agent 的 Skills 目录，然后在对话中输入：

```
帮我写斗叁千臻选土菜研究院的食记
```

Agent 会自动搜索大众点评/小红书等平台的真实评论，按七大引擎生成食记。

## 写作示例

以下是 v3.0 为「斗叁千·臻选土菜研究院」（苏州）生成的食记：

> **塔园路这家土菜馆，人均120吃出了请客的排面**
>
> 加班到九点从塔园路地铁站出来，肚子叫得整栋写字楼都听见了。抬头看见易生活广场还亮着灯，斗叁千门口的大台阶像在跟我招手。
>
> 门口的大台阶先给你一个下马威，走上去才看到招牌。推门进去，最先注意到的是墙上叶圣陶的字画，原木框裱的，不是那种打印店做的廉价货。大厅的灯光偏暖黄，桌子之间距离够宽，不会听见隔壁聊什么。包厢更安静些，每个包间门上都挂了木牌，一股旧时私塾的味道。服务员领位的时候顺手就把椅子拉开了，没等你动手。
>
> 鱼头豆腐汤端上来的时候汤还在冒泡，乳白色的，看着就踏实。第一口是鱼鲜，嚼到第三下豆腐的豆香才出来，紧接着是泡椒的微辣回口。说实话，比我在杭州吃的鱼头汤多了层泡椒的筋骨，没那么寡淡。一大盆128，两个人喝完刚刚好。
>
> 梅干菜牛肉炒饭端上来的时候卖相一般，黑乎乎的，差点没拍照。结果一勺子下去，锅气重到爆，牛肉粒有嚼劲不柴，梅干菜吸饱了油带一点甜。偷偷说一句，这个38块的炒饭比牛肋骨好吃多了。
>
> 地铁1号线塔园路站2出口，走5分钟进易生活广场一楼。逛完去隔壁绿宝广场溜一圈，或者开车10分钟到寒山寺，刚好消食。
>
> 走到地铁站的路上还在咂摸那个鱼汤的鲜，这大概就是吃完斗叁千的正常反应。你们要是去的话，记得先点炒饭垫垫肚子，别问我怎么知道的。

## 版本历史

| 版本 | 日期 | 核心变更 |
|------|------|----------|
| v1.0 | 2026-06-30 | 初始版：四不四要、三阶段结构、7项自检 |
| v2.0 | 2026-06-30 | 五引擎架构：钩子/五感/人设/反差 |
| v2.1 | 2026-06-30 | 新增环境空间叙事引擎，自检12项 |
| v3.0 | 2026-06-30 | **产品化版本**：标题工厂+类型适配+17项自检+分发就绪 |

详见 [CHANGELOG.md](./CHANGELOG.md)

## 定价

| 版本 | 功能 | 价格 |
|------|------|------|
| 免费版 | 七大引擎、基础写作、单个店铺 | 免费 |
| 标准版 | +优先队列 + 批量生成（月50篇）+ 数据导出 | 19.9元/月 |
| 商业授权 | 用于代写服务/商业分发 | 联系作者 |

## 许可证

本仓库中的 SKILL.md 以 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 协议开源。个人使用免费，商业用途需单独授权。

---

## 作者

- 版本：v3.0
- 首次发布：2026年6月30日
- 协议：CC BY-NC-SA 4.0

有问题或合作意向？欢迎在 [Issues](https://github.com/yourusername/dianping-shiji/issues) 区留言。
*（内容由AI生成，仅供参考）*
*（内容由AI生成，仅供参考）*
