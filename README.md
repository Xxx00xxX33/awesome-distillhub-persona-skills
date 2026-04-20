
# DistillHub 🌌 — Awesome Persona Distillation Skills

**同事.skill、前任.skill、女娲.skill、Forge Skill、反蒸馏 Skill、自己.skill……**

> **想象一下：**  
> 把你的同事、前任、导师、甚至马斯克、张一鸣、费曼的完整思维方式，全部“蒸馏”成一个**可在 DistillHub 客户端一键导入**的 .skill。  
> 从此，你拥有了自己的数字同事、赛博父母、思维导师、情感伴侣……  
> **DistillHub** —— 让数字永生、个人思维操作系统和 Agent 群聊编排真正落地。  
> **万物皆可 skill**，与其等着被别人蒸，不如先蒸自己！


[![Stars](https://img.shields.io/github/stars/codeman008/awesome-distillhub-persona-skills?style=social)](https://github.com/codeman008/awesome-distillhub-persona-skills)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

**🚀 一键使用指南（超简单 3 秒上手）**  
所有 Skill 都支持以下**最简单**的使用方式：

1. **最推荐**：打开 DistillHub 客户端 → 左侧「Skill 市场」→ 搜索仓库名 → **一键导入**（自动下载并加载）。
2. **手动拖拽**：点击下方表格里的仓库链接 → 下载仓库里的 `.skill` 文件 → 直接拖进 DistillHub 窗口。
3. **CLI 一行命令**（适合开发者）：  
   ```bash
   distillhub import https://github.com/codeman008/awesome-distillhub-persona-skills
   ```
4. **网页版快速试用**：部分 Skill 支持在线预览，直接点仓库链接 → 点「Try in DistillHub」按钮。

**表格里的链接全部使用最原始的 GitHub 地址**，点一下就能直接跳转，方便大家复制粘贴或浏览器打开。

---

## 📋 DistillHub目录（2026.04更新）
- [skill商店整理](#skill商店整理)
- [1. DistillHub核心元工具与蒸馏器](#1-distillhub-核心元工具与蒸馏器)
- [2. 职场与团队协作](#2-职场与团队协作)
- [3. 情感·关系·记忆](#3-情感关系记忆)
- [4. 方法论·思维操作系统](#4-方法论思维操作系统)
- [5. 流行文化与网红生态](#5-流行文化与网红生态)
- [6. 玄学·精神·未来主义](#6-玄学精神未来主义)
- [7. 平台集成与Agent编排](#7-平台集成与-agent-编排)
- [8. 伦理·隐私·反蒸馏](#8-伦理隐私反蒸馏)
- [9. 数字遗产与永生蓝图](#9-数字遗产与永生蓝图)
- [DistillHub 生态工具箱](#distillhub-生态工具箱)

---
## skill商店整理
本表旨在为开发者及 AI 工程师提供高质量的技能（Skills/Actions/Connectors）资源索引，内容来源涵盖大厂生态、开发者社区及优质开源项目。
这些平台代表了当前工业界将 AI 接入业务系统的最高标准，是研究 API Schema 和交互协议的核心来源。

| 技能商店/平台 | 归属方 | 主要应用场景 | 工程化参考价值 |
| :--- | :--- | :--- | :--- |
| **[Copilot Studio Connectors](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)** | Microsoft | 企业级业务自动化、CRM、ERP | 标准化连接器规范 (API Schema) |
| **[GPTs Store (Actions)](https://openai.com/gpt-store)** | OpenAI | 垂直领域智能助手、插件扩展 | 自然语言接口定义 (Action JSON) |
| **[Vertex AI Agent Builder](https://cloud.google.com/vertex-ai/agent-builder)** | Google | 企业知识库检索、搜索集成 | 模块化技能封装、高可用链路 |
| **[Agentforce Directory](https://www.salesforce.com/agentforce/)** | Salesforce | 销售自动化、客服、CRM逻辑 | 业务合规性处理、安全逻辑 |
| **[Zapier AI Actions](https://zapier.com/ai-actions)** | Zapier Inc. | 全生态工具联动 (6000+应用) | 高并发下的接口调度范式 |
| **[GitHub MCP Registry](https://github.com/modelcontextprotocol/servers)** | Anthropic 及社区 | 本地 AI 协议标准化 | 跨平台本地工具集成 |
| **[Refly](https://refly.ai/)** | Refly.ai 团队 | 无代码构建、企业级治理 | 团队工作流、企业 S.O.P |
| **[Skills.sh](https://skills.sh/)** | Vercel Labs | CLI 即用、跨框架兼容 | 开发者 CLI 工作流 |
| **[SkillsMP](https://skillsmp.com/)** | 社区聚合项目 | 20万+ 海量资源、语义搜索 | 全栈开发、多工具联动 |
| **[Skillstore.io](https://skillstore.io/)** | AISkillStore 社区 | 自动化安全审计、高质量精选 | 高合规行业 |
| **[SkillsLM](https://skillslm.com/)** | 独立开发者社区 | 结构化教程、系统化学习 | AI Agent 初学者入门 |
## 1. DistillHub 核心元工具与蒸馏器
它让你把「自己」变成可编程的思维模块，同时提供创建、进化、保护其他 Skill 的元能力。  
无论你是想打造第二个自己、实现数字永生，还是想安全地蒸馏他人思维，这里都是起点。  
**女娲.skill + Forge Skill + 反蒸馏 Skill** 组合使用，几乎能满足所有进阶玩法。

| 名字              | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|-------------------|-------------------------------------------------------------|------|
| 自己.skill       | [https://github.com/notdog1998/yourself-skill](https://github.com/notdog1998/yourself-skill) | 个人思维操作系统，从聊天记录蒸馏自我 |
| 永生.skill       | [https://github.com/agenmod/immortal-skill](https://github.com/agenmod/immortal-skill) | 多维度数字永生框架 |
| 数字人生.skill   | [https://github.com/wildbyteai/digital-life](https://github.com/wildbyteai/digital-life) | 从日常数字痕迹提取结构化自我 |
| 反蒸馏 Skill     | [https://github.com/leilei926524-tech/anti-distill](https://github.com/leilei926524-tech/anti-distill) | 公开 Skill 与私有经验分离 |
| 女娲.skill       | [https://github.com/alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | 万能蒸馏器，可提取任何人思维模型 |
| Forge Skill      | [https://github.com/YIKUAIBANZI/forge-skill](https://github.com/YIKUAIBANZI/forge-skill) | 自我/他人蒸馏分离 + 记忆整理 |
| Persona-Skill    | [https://github.com/Tomsawyerhu/Persona-Skill](https://github.com/Tomsawyerhu/Persona-Skill) | 人格合成器：生物、引用、聊天记录一键融合多个人格 |
| 八字人格         | [https://github.com/jinchenma94/bazi-skill](https://github.com/jinchenma94/bazi-skill) | 基于生辰八字，生成会聊天、有情绪、会随时间变化的AI人格 |
| 图鉴.skill       | [https://github.com/Aar0nPB/curator-skill](https://github.com/Aar0nPB/curator-skill) | 跨作者 persona skill 调度器 — 根据对话意图，从 30 个 persona skill 中智能匹配推荐 |
| midas.skill      | [https://github.com/realteamprinz/midas-skill](https://github.com/realteamprinz/midas-skill) | 从任意公众人物中提炼六维度财富操作系统（也可从个人数据挖掘财富信号） |
| VibePortrait     | [https://github.com/dadwadw233/VibePortrait](https://github.com/dadwadw233/VibePortrait) | 从 Vibe Coding 对话中提炼开发者画像、开发技能与偏好 |
| 诸子.skill       | [https://github.com/linzzzzzz/zhuzi-skill](https://github.com/linzzzzzz/zhuzi-skill) | 让多个已存在的人格 skill 围绕同一问题展开结构化辩论，支持自动选人、按轮交锋与中立总结 |

---

## 2. 职场与团队协作
**把真实同事、老板、导师「搬进」AI，让工作和学习效率直接起飞。**  
这些 Skill 保留了对方的工作习惯、决策逻辑、沟通风格和专业知识，能帮你自动回复消息、起草方案、预测老板反馈、甚至模拟学术指导。  
尤其适合离职交接、项目救火、备考复习等场景，真正实现「数字替身」式生产力升级。

| 名字                        | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|-----------------------------|-------------------------------------------------------------|------|
| 同事.skill                 | [https://github.com/titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) | 从团队材料中蒸馏已离职同事的工作习惯与沟通风格 |
| 老板.skill                 | [https://github.com/vogtsw/boss-skills](https://github.com/vogtsw/boss-skills) | 提取管理者判断标准、批阅风格与沟通预期 |
| 师兄.skill                 | [https://github.com/zhanghaichao520/senpai-skill](https://github.com/zhanghaichao520/senpai-skill) | 蒸馏师兄的指导风格与危机处理方式 |
| 导师.skill                 | [https://github.com/ybq22/supervisor](https://github.com/ybq22/supervisor) | 导师指导风格蒸馏，随时可用 |
| 大学老师.skill             | [https://github.com/CommitHu502Craft/professor-skill](https://github.com/CommitHu502Craft/professor-skill) | 提取课程复习重点、题型偏好与评分线索 |
| HR.skill                   | [https://github.com/Schlaflied/hr-skill](https://github.com/Schlaflied/hr-skill) | 从拒信与招聘流程中整理 HR 的沟通逻辑与决策模式，用于反向拆解筛选标准并重构求职叙事 |
| roast-cold-email-skill     | [https://github.com/Schlaflied/roast-cold-email-skill](https://github.com/Schlaflied/roast-cold-email-skill) | 从公司公开信息与招聘材料中整理批评性求职邮件写法，用于生成有理有据的冷联系求职邮件 |

---

## 3. 情感·关系·记忆
**情感陪伴与数字永生的最柔软角落。** 支持微信/照片/朋友圈持续进化

| 名字                        | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|-----------------------------|-------------------------------------------------------------|------|
| 暗恋对象.skill             | [https://github.com/xiaoheizi8/crush-skills](https://github.com/xiaoheizi8/crush-skills) | 从聊天、照片中提取心动瞬间的沟通风格 |
| 恋爱训练营.skill           | [https://github.com/TammyTan516/relationship-training-skill](https://github.com/TammyTan516/relationship-training-skill) | 在安全沙盒中模拟暗恋对象风格 |
| 前任.skill                 | [https://github.com/therealXiaomanChu/ex-skill](https://github.com/therealXiaomanChu/ex-skill) | 从私密记录中提取言语模式与共同记忆 |
| 前任.skill（Claude Code 版） | [https://github.com/perkfly/ex-skill](https://github.com/perkfly/ex-skill) | 微信/iMessage/照片一键创建，支持持续进化 |
| 父母.skill                 | [https://github.com/xiaoheizi8/parents-skills](https://github.com/xiaoheizi8/parents-skills) | 提取父母语气、习惯与家庭记忆 |
| MamaSkill                  | [https://github.com/jiangziyan-693/MamaSkill](https://github.com/jiangziyan-693/MamaSkill) | 从聊天、信件、语音中构建家庭陪伴助手 |
| Reunion Skill              | [https://github.com/yangdongchen66-boop/reunion-skill](https://github.com/yangdongchen66-boop/reunion-skill) | 本地运行的逝者纪念陪伴助手 |
| 兄弟.skill                 | [https://github.com/realteamprinz/brother-skill](https://github.com/realteamprinz/brother-skill) | 从抖音、微信截图等来源蒸馏你的兄弟们（真实兄弟、群聊好友、网络红人）——说话方式、口头禅、搞笑风格 |

---

## 4. 方法论·思维操作系统

**把顶级思维模型「收入囊中」，让 AI 成为你的专属智囊团。**  
特朗普的谈判风格、马斯克的第一性原理、芒格的多元思维、费曼的解释力……  
加载对应 Skill 后，你可以随时让 AI 用这些大师的框架帮你分析问题、制定策略、写文章、做决策。  
这是 DistillHub 中最受高端用户欢迎的「思维操作系统」集合。

| 名字                        | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|-----------------------------|-------------------------------------------------------------|------|
| 特朗普.skill               | [https://github.com/alchaincyf/trump-skill](https://github.com/alchaincyf/trump-skill) | 谈判/权力/传播框架 |
| 马斯克.skill               | [https://github.com/alchaincyf/elon-musk-skill](https://github.com/alchaincyf/elon-musk-skill) | 第一性原理思考框架 |
| 乔布斯.skill               | [https://github.com/alchaincyf/steve-jobs-skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略思维 |
| 巴菲特思维操作系统         | [https://github.com/will2025btc/buffett-perspective](https://github.com/will2025btc/buffett-perspective) | 巴菲特投资决策框架 |
| 芒格.skill                 | [https://github.com/alchaincyf/munger-skill](https://github.com/alchaincyf/munger-skill) | 多元思维/逆向思考 |
| 费曼.skill                 | [https://github.com/alchaincyf/feynman-skill](https://github.com/alchaincyf/feynman-skill) | 解释风格与求真启发式 |
| 户晨风.skill               | [https://github.com/Janlaywss/hu-chenfeng-skill](https://github.com/Janlaywss/hu-chenfeng-skill) | 购买力挑战视角分析消费与职业 |
| 童锦程.skill               | [https://github.com/hotcoffeeshake/tong-jincheng-skill](https://github.com/hotcoffeeshake/tong-jincheng-skill) | 人际情感判断直白视角 |
| 张一鸣.skill               | [https://github.com/alchaincyf/zhang-yiming-skill](https://github.com/alchaincyf/zhang-yiming-skill) | 产品/组织/全球化思维 |
| 纳瓦尔.skill               | [https://github.com/alchaincyf/naval-skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 |
| 塔勒布.skill               | [https://github.com/alchaincyf/taleb-skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 |
| Paul Graham.skill          | [https://github.com/alchaincyf/paul-graham-skill](https://github.com/alchaincyf/paul-graham-skill) | 创业思考框架 |
| Karpathy.skill             | [https://github.com/alchaincyf/karpathy-skill](https://github.com/alchaincyf/karpathy-skill) | AI/深度学习思维 |
| X 导师.skill               | [https://github.com/alchaincyf/x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill) | 写作/内容增长导师 |
| Khazix Skills.skill        | [https://github.com/KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) | 写作/数字生命卡兹克开源的 AI Skills 合集 |
| 峰哥亡命天涯 Skill         | [https://github.com/Walshyu/fengge-skill](https://github.com/Walshyu/fengge-skill) | 现实主义、止损导向与黑色幽默式表达结构 |
| 郭德纲.skill               | [https://github.com/ByteRax/guodegang-skills](https://github.com/ByteRax/guodegang-skills) | 表达结构、处世判断与职业方法 |
| liangxi-skills             | [https://github.com/1sh1ro/liangxi-skills](https://github.com/1sh1ro/liangxi-skills) | 结构判断、风险习惯与中文交易表达 |
| 毛选.skill                 | [https://github.com/leezythu/maoxuan-skill](https://github.com/leezythu/maoxuan-skill) | 矛盾分析、根据地思维与战略判断框架 |
| 新青年.Skill               | [https://github.com/SamadhiFire/xinqingnian-skill](https://github.com/SamadhiFire/xinqingnian-skill) | 把《毛选》157篇文章蒸馏成可执行的现实分析 skill |
| 张雪峰.skill               | [https://github.com/alchaincyf/zhangxuefeng-skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 升学、考试与职业规划的实战框架 |
| zizek-skill                | [https://github.com/JikunR/zizek-skill](https://github.com/JikunR/zizek-skill) | 前提追问、欲望追踪与矛盾揭示方法 |
| 求是 Skill                 | [https://github.com/HughYau/qiushi-skill](https://github.com/HughYau/qiushi-skill) | 从教员思想中提炼实事求是、调查研究与战略判断工具 |

---

## 5. 流行文化与网红生态
**快速获取当下最火的内容创作与生活方式模板。**  
宝玉、花叔、MrBeast 的内容风格，小红书运营技巧，赛博老婆/她人格引擎，甚至多人智者议会……  
无论你是想批量生产爆款内容、打造个人 IP，还是需要情感陪伴或多视角决策，这里都能一键满足。  
最适合内容创作者、运营者和追求潮流玩法的用户。

| 名字            | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|-----------------|-------------------------------------------------------------|------|
| 宝玉            | [https://github.com/JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills) | 网红博主技能合集 |
| 花叔            | [https://github.com/alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | 网红博主技能 |
| MrBeast         | [https://github.com/alchaincyf/mrbeast-skill](https://github.com/alchaincyf/mrbeast-skill) | MrBeast 风格技能 |
| 赛博老婆        | [https://github.com/Syan-Lin/CyberWaifu](https://github.com/Syan-Lin/CyberWaifu) | 情感虚拟伴侣引擎 |
| 她人格引擎      | [https://github.com/kellyvv/OpenHer](https://github.com/kellyvv/OpenHer) | 女性人格引擎 |
| 小红书运营      | [https://github.com/white0dew/XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) | 小红书内容运营技能 |
| 智者议会        | [https://github.com/linxumoney/wisdom-council](https://github.com/linxumoney/wisdom-council) | 多位智者联合决策框架 |
| 内娱.skill      | [https://github.com/yanghaoraneve/star-skill](https://github.com/yanghaoraneve/star-skill) | 从歌词、视频、微博与评论中整理歌手或偶像的表达风格与互动方式 |

---

## 6. 玄学·精神·未来主义

**传统智慧与现代 AI 的奇妙融合。**  
赛博算命、四柱八字、月老姻缘、佛教大师教学风格……  
这些 Skill 把古老的命理、哲学、精神指导搬进了对话系统，既能娱乐解压，也能提供人生指引和心灵慰藉。  
在理性工具之外，给你一点「玄学浪漫」和精神陪伴。

| 名字              | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|-------------------|-------------------------------------------------------------|------|
| 赛博算命.skill   | [https://github.com/jinchenma94/bazi-skill](https://github.com/jinchenma94/bazi-skill) | 四柱八字专业分析 |
| 月老.skill       | [https://github.com/Ming-H/yinyuan-skills](https://github.com/Ming-H/yinyuan-skills) | 赛博月老算姻缘 |
| 佛教大师.skill   | [https://github.com/xr843/Master-skill](https://github.com/xr843/Master-skill) | 汉传祖师教学风格 |
| 金刚经.skill     | [https://github.com/dull-bird/diamond-sutra-skill](https://github.com/dull-bird/diamond-sutra-skill) | 基于《金刚经》整理佛学讲解框架 |
| 堪舆子           | [https://github.com/voidforall/fengshui.skill](https://github.com/voidforall/fengshui.skill) | 传统堪舆（玄空飞星、八宅明镜、择日）风水顾问技能 |

---

## 7. 平台集成与 Agent 编排
**专为 DistillHub 客户端设计的多 Agent 协同能力。**

| 名字                            | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|---------------------------------|-------------------------------------------------------------|------|
| DistillHub Orchestrator.skill   | [https://github.com/codeman008/distillhub-orchestrator](https://github.com/codeman008/distillhub-orchestrator) | 多 Skill 自动编排 + 任务拆解 |
| Multi-Persona Council.skill     | [https://github.com/codeman008/multi-persona-council](https://github.com/codeman008/multi-persona-council) | 10 位大师同时在线决策 |
| Voice & Video Distill.skill     | [https://github.com/codeman008/multimodal-distill](https://github.com/codeman008/multimodal-distill) | 支持语音/视频多模态蒸馏 |
| Distill-Protocol.skill          | [https://github.com/agenmod/immortal-skill/tree/main/distill-protocol-skill](https://github.com/agenmod/immortal-skill/tree/main/distill-protocol-skill) | 七维数字分身协议（12+ 平台聊天记录） |

---

## 8. 伦理·隐私·反蒸馏
**2026 年最重要的话题：保护自己不被恶意蒸馏。**

| 名字                     | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|--------------------------|-------------------------------------------------------------|------|
| 反蒸馏 Skill（增强版）  | [https://github.com/leilei926524-tech/anti-distill](https://github.com/leilei926524-tech/anti-distill) | 核心知识自动清洗 |
| Privacy Vault.skill      | [https://github.com/codeman008/privacy-vault](https://github.com/codeman008/privacy-vault) | 本地加密记忆保险箱 |
| Ethical Distill Guard    | [https://github.com/codeman008/ethical-guard](https://github.com/codeman008/ethical-guard) | 蒸馏前自动伦理审查 |

---

## 9. 数字遗产与永生蓝图
**把人生真正变成可继承的数字资产。**

| 名字                | 仓库地址（原始链接，点击直达）                                      | 介绍 |
|---------------------|-------------------------------------------------------------|------|
| 数字遗产.skill     | [https://github.com/codeman008/digital-legacy](https://github.com/codeman008/digital-legacy) | 遗嘱式永生框架 |
| 永生蓝图 2.0       | [https://github.com/agenmod/immortal-blueprint-v2](https://github.com/agenmod/immortal-blueprint-v2) | 支持后代继承的进化版 |

---

## DistillHub 生态工具箱
- **DistillHub Desktop / Web 客户端**（官方下载）
- **Forge Skill 锻造器**（可视化蒸馏界面）
- **一键导入脚本**（Chrome 插件 / CLI）
- **Skill 热更新中心**（社区最新 Skill 自动推送）
- **本地隐私模式**（零云端，全部跑在你的电脑上）

---

**Star History**  
![Star History](https://api.star-history.com/svg?repos=codeman008/awesome-distillhub-persona-skills&type=Date)

---

## 贡献指南
欢迎 PR 补充 **DistillHub 专属 Skill**！  
优先收录已在 DistillHub 客户端测试通过的 .skill 文件。  
Fork → 修改表格 → 提交 PR，标题带 `feat: 新增 XXX Skill（DistillHub 支持）`

## 📢 项目声明

**本项目所有内容均来源于网上公开资料的整理与汇总**，并借助大模型（LLM）进行归类、总结和结构化处理。

- 本项目**未继承、未fork、未复制**任何特定项目的代码、文档或完整内容；
- 所有素材均来自互联网公开可获取的信息，不涉及任何私有、付费或受版权保护的专有资料；
- 项目中可能出现的任何雷同内容，纯属因公开资料本身高度相似所致，并非有意抄袭或继承。

本项目仅供学习、研究和交流使用，不做任何商业用途。项目作者不对内容的准确性、完整性及合法性承担任何法律责任。
