<h1 align="center">你好 👋，我是王文博</h1>
<h3 align="center">🤖 从0到1的AI Agent产品经理 | 多智能体架构实践者</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=wangwenbo0305&label=Profile%20views&color=0e75b6&style=flat" alt="wangwenbo0305" />
</p>

---

## 🧑‍💻 关于我

- 🎯 **AI原生产品经理**，具备从0到1独立设计AI Agent产品的完整实战经验
- 🏢 **百度**品牌广告AI产品经理，主导Agent投放与多模态风控产品建设
- 🤖 深入理解AI Agent全链路架构：Memory | 知识库 | RAG | Skills | MCP | Tool Use
- 📊 熟练运用SQL + Python进行数据驱动决策，具备ML/DL算法基础
- 🌱 持续跟踪Agentic Workflow、多Agent协作等前沿动态并落地业务场景

---

## 🏆 核心成就

| 项目 | 成果 |
|------|------|
| **百度品牌广告AI Agent** | 迁移成功率92%，投放链路步骤减少60%，人力成本降低98% |
| **多模态风控审核系统** | 审核效率提升87.5%，误判率下降70.8%，长尾召回率提升23.6% |
| **Price-Agent商品比价助手** | 从0到1独立设计AI搜索Agent，7阶段158+用例评测体系 |
| **TalkingData广告欺诈检测** | 2亿数据LightGBM建模，AUC 0.96，欺诈召回率93% |

---

## 🛠️ 技术栈

### AI Agent 核心能力
<p align="left">
  <img src="https://img.shields.io/badge/LLM-OpenAI%2FClaude%2FDeepSeek-blue?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-LangChain%2FLlamaIndex-green?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Agent_Architecture-ReAct%2FPlan--Execute-orange?style=for-the-badge&logo=robot&logoColor=white" />
  <img src="https://img.shields.io/badge/微调-SFT%2FRLHF%2FLoRA-red?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Agent工具-MCP%2FSkills%2FToolUse-purple?style=for-the-badge" />
</p>

### 编程与数据
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

### 产品与工具
<p align="left">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Axure-000000?style=for-the-badge&logo=axure&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
</p>

---

## 💼 工作经历

### **百度** | 品牌广告 AI 产品经理
*2025.08 - 2026.04*

**一键百看生成 & 投放能力建设 Agent**
- 设计多渠道素材统一资产数据模型，整合品专历史物料与官网抓取等多源数据，自动生成主KV卡、官网卡、服务卡、商品卡、下载卡等结构化资产卡
- 主导品专历史物料迁移Agent设计，规划Logo多级回源策略（物料供给 → 平台供给 → 官网抓取）
- 设计资产-买词语义匹配策略，基于素材内容解析匹配买词集合，解决资产入库卡点
- 设计智能助手任务编排与节点管理框架，串联资产生成、问答生成、调度触达等模块，形成「资产选择 → 意图匹配 → 一键提交」标准化执行闭环

**多模态风控审核优化**
- 协同风控策略团队搭建品牌广告全场景多模态训练数据供给体系
- 设计"大模型分级预审 → 高置信度自动过审 → 低置信度人工复核"的 AI+人工协同审核链路
- 落地视频智能抽帧与全模态时序风险识别能力

---

## 🚀 代表项目

### Price-Agent 商品对比智能助手 🔗 [GitHub: price-agent](https://github.com/wenbo030509/price-agent)
*从0到1独立设计的AI搜索Agent产品*

- **产品架构**：规划 ReAct + Plan-Execute + 语义推荐三模式混合策略；设计意图分类路由模块，自动识别"比价/对比/推荐/混合"四类意图并路由至最优执行路径
- **自反思纠错**：工具返回空结果时自动注入反思提示引导重试，有效降低幻觉率
- **IT3C行业优化**：针对手机品类设计17字段商品数据模型与归一化别名体系，构建7类使用场景标签；8维度属性评分驱动推荐排序
- **上下文设计**：滑动窗口上下文管理 + 子步骤引用语法 + 多模态图片识物自动转比价
- **分层评测**：7阶段分层评测方案（P0-P6），覆盖158+测试用例，评测结论驱动关键迭代

### TalkingData 广告点击欺诈检测 🔗 [GitHub: talkingdata-ad-fraud-detection](https://github.com/wenbo030509/talkingdata-ad-fraud-detection)

- 处理2亿条点击数据，解决正负样本1:33极度不平衡分类问题
- IP分桶策略分布式特征工程，构建四类高维统计特征
- LightGBM + 网格搜索 + EarlyStopping，模型AUC 0.96，欺诈召回率93%

---

## 📊 GitHub 统计数据

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=wangwenbo0305&show_icons=true&locale=cn&theme=radical" alt="wangwenbo0305" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=wangwenbo0305&theme=radical" alt="wangwenbo0305" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wangwenbo0305&show_icons=true&locale=cn&layout=compact&theme=radical" alt="wangwenbo0305" />
</p>

---

## 🏅 资质认证

- **阿里云大数据助理工程师（ACA）**
- **英语**：雅思6.5（6） / CET6，可熟练阅读英文技术文档

---

## 📫 联系我

<p align="center">
  <a href="mailto:wangwenbo030509@163.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-wangwenbo030509@163.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🎯 2026年目标

- [ ] 深入研究自主多智能体系统和Agentic Workflow
- [ ] 为开源LLM/Agent框架贡献代码
- [ ] 构建个人AI Agent作品集，展示端到端产品思维
- [ ] 掌握先进的RLHF和模型对齐技术

---

<p align="center">
  <em>"打造放大人类潜力的智能Agent。" 🚀</em>
</p>
