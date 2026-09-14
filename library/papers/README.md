# 🎓 学术论文书库（40 篇）

> 📚 本页是 OpenGEO 的**学术论文书库**，收录经同行评议的会议论文与高相关预印本（KDD、NeurIPS、ICLR、ICML、ACL、EMNLP、SIGIR、EACL、FAccT 及 arXiv），按主题分为五个分区，共 **40** 篇。
>
> 每条包含：标题、作者与出处、主题标签、一句话总结与原文链接。论文 PDF 原件（含封面卡片与附件下载）保留在[飞书知识库书库页](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)；**出于版权与仓库体积考虑，本仓库不托管 PDF 文件**。
>
> 行业报告、白皮书与中国市场资料不属于学术论文，统一收录在 [📰 行业报告书库](../reports/README.md)。资料分级：正式发表会议论文优先级最高；arXiv 预印本需注意版本变化。

## 目录

- [一、核心综述与奠基（3）](#一-核心综述与奠基)
- [二、优化方法与基准（16）](#二-优化方法与基准)
- [三、测量、引用与商业影响（13）](#三-测量-引用与商业影响)
- [四、安全、操纵与治理（7）](#四-安全-操纵与治理)
- [五、中文译文与导读（1）](#五-中文译文与导读)


## 一、核心综述与奠基（3）

### 1. Optimizing Visibility in Generative Engines: A Critical Survey of GEO (2023–2026)

*Olivier Martinez · arXiv 综述 · 2026 · 18 页* ｜ `综述` ｜ `预印本`

系统综述 2023 年 11 月至 2026 年 7 月间的 45 项 GEO 研究，指出 GEO 是覆盖抓取索引、检索重排、引用、内容吸收与用户行为的随机可观测管线；奠基论文的增益结论有严格实验前提，不能直接外推到自然流量。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2607.14035) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 2. GEO: Generative Engine Optimization

*Pranjal Aggarwal 等（IIT Delhi / Princeton）· KDD 2024 · 12 页* ｜ `奠基论文`

GEO 领域奠基论文，首次形式化“生成式引擎”概念并提出九类可见性优化策略，实验证明加入统计数据、直接引述等风格改写可显著提升内容在 AI 答案中的可见度与被引率。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2311.09735) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 3. Evaluating Verifiability in Generative Search Engines

*Nelson F. Liu, Tianyi Zhang, Percy Liang（Stanford）· EMNLP Findings 2023 · 25 页* ｜ `引用质量` ｜ `评测基准`

人工审计 Bing Chat、NeevaAI、Perplexity、YouChat 四款生成式搜索引擎，发现平均仅 51.5% 的回答句子有引用充分支撑、74.5% 的引用与其语句匹配，揭示 AI 答案的可验证性短板。

- 🔗 [原文链接 ↗](https://aclanthology.org/2023.findings-emnlp.467/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)


## 二、优化方法与基准（16）

### 4. C-SEO Bench: Do Conversational Search Engine Optimization Methods Work?

*Haritz Puerto, Martin Gubri, Tommaso Green 等 · NeurIPS 2025 D&B · 25 页* ｜ `评测基准`

首个跨任务、跨领域、多参与者竞争场景的对话式 SEO（C-SEO）基准，发现常见 GEO 方法在广泛领域与多方同时优化的竞争条件下经常失效，单文档实验结论并不可靠。

- 🔗 [原文链接 ↗](https://proceedings.neurips.cc/paper_files/paper/2025/hash/27aa3aeff0f8460a7b43d30fa6c5c032-Abstract-Datasets_and_Benchmarks_Track.html) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 5. What Generative Search Engines Like and How to Optimize Web Content Cooperatively (AutoGEO)

*Yujiang Wu, Shanshan Zhong, Yubin Kim, Chenyan Xiong · ICLR 2026 · 30 页* ｜ `优化方法` ｜ `内容改写`

让前沿大模型自动解释并归纳生成式引擎的内容偏好规则，再以规则作为上下文工程与奖励信号，驱动低成本小模型协同改写网页内容，在 GEO-Bench 等基准上稳定提升引用可见性。

- 🔗 [原文链接 ↗](https://openreview.net/forum?id=K8EinVWtUB) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 6. E-GEO: A Testbed for Generative Engine Optimization in E-Commerce

*Puneet S. Bagga, Vivek F. Farias 等（MIT 等）· arXiv 预印本 · 2025 · 54 页* ｜ `评测基准` ｜ `电商场景`

首个面向电商的 GEO 测试床，含 13,747 条真实多句购物查询与配对的亚马逊商品页，跨五个生成式引擎、七个改写模型与十五条人工启发式规则完成首次大规模电商 GEO 实证。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2511.20867) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 7. SAGEO Arena: A Realistic Environment for Evaluating Search-Augmented GEO

*Sunghwan Kim 等（Yonsei University）· arXiv 预印本 · 2026 · 12 页* ｜ `评测基准` ｜ `端到端`

端到端复现“检索—重排—生成”全链路的 SAGEO 评测环境，保留真实网页的结构化信息（如 schema 标记），支持分阶段度量优化策略从被检索到被引用的真实影响。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2602.12187) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 8. Think Before Writing: Feature-Level Multi-Objective Optimization for Generative Citation Visibility (FeatGEO)

*Zikang Liu, Peilan Xu（南京信息工程大学）· ACL 2026 · 14 页* ｜ `优化方法` ｜ `特征工程`

把网页抽象为结构、内容、语言三类可解释特征，在特征空间而非词元层面做多目标优化，再由模型把特征配置落为自然语言，在三个生成式引擎上同时提升引用可见性并保持内容质量。

- 🔗 [原文链接 ↗](https://aclanthology.org/2026.acl-long.929/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 9. Mind Reader: Latent User Demand-Guided Content Optimization for Generative Search Engine

*Tong Chen, Jiawei Guo 等 · ACL 2026 · 17 页* ｜ `优化方法` ｜ `查询理解`

通过“分解—重组”查询增强挖掘用户潜在搜索意图，再以推理覆盖度为导向优化内容，让网页更贴合驱动 AI 检索与回答生成的隐性需求，从而提升内容可见性。

- 🔗 [原文链接 ↗](https://aclanthology.org/2026.acl-long.1894/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 10. IF-GEO: Conflict-Aware Instruction Fusion for Multi-Query Generative Engine Optimization

*Heyang Zhou 等（中国科学技术大学）· ACL Findings 2026 · 15 页* ｜ `优化方法` ｜ `多查询`

针对异构查询对同一文档提出相互冲突的修改要求，提出“先发散后收敛”的指令融合框架，汇总形成全局修改蓝图，并引入风险感知的跨查询稳定性度量。

- 🔗 [原文链接 ↗](https://aclanthology.org/2026.findings-acl.1373/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 11. From Experience to Skill: Multi-Agent GEO via Reusable Strategy Learning (MAGEO)

*Beining Wu, Fuyou Mao 等（杭州电子科技大学等）· ACL Findings 2026 · 11 页* ｜ `多智能体` ｜ `优化方法`

把 GEO 重构为策略学习问题：规划、编辑、保真评估多智能体协同执行，并把被验证的编辑模式逐步蒸馏为可复用、分引擎的优化技能，可见性与引用保真度均显著优于启发式基线。

- 🔗 [原文链接 ↗](https://aclanthology.org/2026.findings-acl.2149/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 12. AgenticGEO: A Self-Evolving Agentic System for Generative Engine Optimization

*Jiaqi Yuan, Jialu Wang 等 · arXiv 预印本 · 2026 · 16 页* ｜ `智能体` ｜ `优化方法`

自进化智能体框架，把优化建模为内容条件控制问题，通过多智能体协作与经验积累强化内容内在质量，以鲁棒适应黑盒引擎不断变化的行为，并大幅降低对引擎交互反馈的依赖。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2603.20213) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 13. CC-GSEO-Bench: A Content-Centric Benchmark for Measuring Source Influence in Generative Search Engines

*Qiyuan Chen, Jiahe Chen 等 · arXiv 预印本 · 2025 · 16 页* ｜ `评测基准` ｜ `信源影响力`

以内容创作者为中心的基准，含 1,000 余篇源文章与 5,000 余查询—文章对，从曝光、忠实归因、因果影响三个维度量化单篇源文章对 AI 合成答案的真实影响力。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2509.05607) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 14. Generative Engine Optimization: How to Dominate AI Search

*Mahe Chen, Xiaoxuan Wang, Kaiwen Chen, Nick Koudas · arXiv 预印本 · 2025 · 27 页* ｜ `信源偏好` ｜ `对比研究`

跨多个垂类、语言与查询改写做大规模受控实验，发现 AI 搜索系统性偏好第三方权威“赢得媒体”而非品牌自有与社交内容，且各引擎在领域多样性、时效性与跨语言稳定性上差异显著。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2509.08919) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 15. Beyond SEO: A Transformer-Based Approach for Reinventing Web Content Optimisation

*Florian Lüttgenau, Imar Colic, Gervasio Ramirez · arXiv 预印本 · 2025 · 9 页* ｜ `优化方法` ｜ `垂直行业`

以旅游网站内容为场景，用 1,905 条清洗后的合成样本微调 BART-base 模型自动改写内容，仿真实验中网页在生成式引擎中的可见性最高提升 30.96%，验证小规模领域微调即可见效。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2507.03169) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 16. Rewrite-to-Rank: Optimizing Ad Visibility via Retrieval-Aware Text Rewriting

*Chloe Ho 等 · arXiv 预印本 · 2025 · 13 页* ｜ `优化方法` ｜ `广告场景`

研究广告文案改写如何影响其在检索系统中的排名与进入 LLM 回答的频次，提出平衡语义相关与内容保真的自定义损失，PPO 模型在不改动检索模型的前提下显著提升广告可见性。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2507.21099) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 17. Generative Engine Optimization: A VLM and Agent Framework for Pinterest Acquisition Growth

*Faye Zhang 等（Pinterest）· arXiv 预印本 · 2026 · 11 页* ｜ `多模态` ｜ `平台实践`

Pinterest 生产级 GEO 框架：反向设计视觉语言模型，让其预测“用户会怎么搜”而非泛泛描述图片内容，再由 AI 智能体挖掘实时互联网趋势，为海量视觉素材补足生成式搜索看重的语义与权威信号。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2602.02961) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 18. Structural Feature Engineering for GEO: How Content Structure Shapes Citation Behavior

*Junwei Yu, Mufeng Yang, Yepeng Ding, Hiroyuki Sato · arXiv 预印本 · 2026 · 10 页* ｜ `结构特征` ｜ `优化方法`

GEO-SFE 框架把内容结构拆为宏观文档架构、中观信息分块、微观视觉强调三层，证明在不改变语义的前提下结构特征本身即可系统性影响引用表现，并给出保语义的结构优化算法。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2603.29979) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 19. Diagnosing and Repairing Citation Failures in Generative Engine Optimization

*Zhihua Tian, Yuhan Chen 等 · arXiv 预印本 · 2026 · 35 页* ｜ `引用机制` ｜ `优化方法`

不再对文档套用统一改写规则，而是建立引用失败模式分类法，由智能体诊断“为什么没被引用”并从工具库选择针对性修复、迭代至成功引用，仅改动 5% 内容即使引用率相对提升超 40%。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2603.09296) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)


## 三、测量、引用与商业影响（13）

### 20. Generative AI Search Engines as Arbiters of Public Knowledge: An Audit of Bias and Authority

*Alice Li, Luanne Sinnamon（University of British Columbia）· arXiv 预印本 · 2024 · 13 页* ｜ `信源偏见` ｜ `审计研究`

对 ChatGPT、Bing Chat、Perplexity 开展为期 7 天、48 个真实查询的审计，发现 AI 回答存在随查询与话题变化的情绪偏见，以及信源的商业与地域偏见，支撑信源高度集中于新闻与数字媒体网站。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2405.14034) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 21. What Evidence Do Language Models Find Convincing?

*Alexander Wan, Eric Wallace, Dan Klein（UC Berkeley）· ACL 2024 · 17 页* ｜ `证据偏好` ｜ `可信度`

构建包含争议性查询与冲突证据文档的 CONFLICTINGQA 数据集，通过敏感性与反事实分析发现：模型判断主要依赖网站与查询的相关性，却在很大程度上忽视人类看重的科学引用等可信度信号。

- 🔗 [原文链接 ↗](https://aclanthology.org/2024.acl-long.403/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 22. Characterizing Web Search in the Age of Generative AI

*Elisabeth Kirsten 等（Ruhr University Bochum / MPI-SWS）· ACL Findings 2026 · 22 页* ｜ `检索行为` ｜ `对比研究`

系统对比 Google 自然搜索与 Google、OpenAI、Perplexity 三家五款生成式搜索，发现各引擎对内部知识与外部信源的依赖、信源多样性和结果稳定性差异显著，合成答案的检索足迹与传统搜索截然不同。

- 🔗 [原文链接 ↗](https://aclanthology.org/2026.findings-acl.526/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 23. How Generative AI Disrupts Search: An Empirical Study of Google Search, Gemini, and AI Overviews

*Riley Grossman 等（New Jersey Institute of Technology）· SIGIR 2026 · 12 页* ｜ `AI Overviews` ｜ `对比研究`

基于 11,500 条真实用户查询对比 Google 自然结果、AI Overviews 与 Gemini：51.5% 的代表性查询触发 AIO 且置于自然结果之上，争议性问题更易触发，三者召回信源平均重合度不足 0.2。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2604.27790) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 24. Don't Measure Once: Measuring Visibility in AI Search (GEO)

*Julius Schulte 等（University of St. Gallen）· arXiv 预印本 · 2026 · 19 页* ｜ `测量方法` ｜ `可见性`

论证 AI 搜索的概率性使单次观测不可靠：答案会随运行次数、提示词与时间波动，品牌 GEO 可见性必须重复测量，并以分布而非单点快照来刻画。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2604.07585) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 25. Measuring Google AI Overviews: Activation, Source Quality, Claim Fidelity, and Publisher Impact

*Haofei Xu, Umar Iqbal 等（Washington University in St. Louis）· arXiv 预印本 · 2026 · 18 页* ｜ `AI Overviews` ｜ `大规模测量`

40 天内对 55,393 条趋势查询的纵向测量：AIO 整体触发率 13.7%、问句查询达 64.7%；被引域名整体比同屏首页结果更可信，但近 30% 不在自然结果中，揭示独立于排名算法的信源选择机制。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2605.14021) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 26. Synthetic Sources?: Auditing Generative Search Engine Citations for Evidence of AI-Generated Sources

*Mowafak Allaham, Nicholas Diakopoulos（Northwestern University）· arXiv 预印本 · 2026 · 22 页* ｜ `信源质量` ｜ `审计研究`

用 712 条真实人类查询审计 ChatGPT、Copilot、Gemini、Perplexity，检验生成式搜索引擎是否会把 AI 生成的“合成信源”当作权威来源引用，评估网络内容 AI 化带来的自我引用风险。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2605.23684) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 27. Answer Bubbles: Information Exposure in AI-Mediated Search

*Michelle Huang 等（University of Illinois Urbana-Champaign）· arXiv 预印本 · 2026 · 16 页* ｜ `信息曝光` ｜ `信源偏见`

跨五个系统分析 11,000 条真实查询的信源多样性、摘要语言特征与源文保真度，发现 AI 摘要系统性偏好维基百科与长内容、弱化对冲措辞，进一步放大引用偏见与信息曝光失衡。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2603.16138) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 28. From Citation Selection to Citation Absorption: A Measurement Framework for GEO Across AI Search Platforms

*张凯、何馨月、姚金刚（独立研究者）· arXiv 预印本 · 2026 · 27 页* ｜ `测量框架` ｜ `引用吸收`

基于 602 个提示、21,143 条搜索层引用与 23,745 条引用特征记录，提出“引用选择—引用吸收”两阶段测量框架，衡量信源从可被发现到真正向答案贡献语言、证据、结构与事实的完整链路。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2604.25707) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 29. What Gets Cited: Competitive GEO in AI Answer Engines

*Rahul Vishwakarma, Shushant Kumar 等（Sprinklr）· SIGIR 2026 · 5 页* ｜ `引用机制` ｜ `竞争实验`

在双文档 RAG 测试床上执行 252,000 次配对比较、检验 18 个内容因素，发现主题相关性与列表位置是“被第一个引用”的最大驱动因素，明确报价与较新的时间戳也有正向作用。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2605.25517) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 30. Disentangling Answer Engine Optimization from Platform Growth: A Log-Based Natural Experiment on ChatGPT Referral Traffic

*Keisuke Watanabe, Kazuki Nakayashiki（Glasp Inc.）· arXiv 预印本 · 2026 · 9 页* ｜ `AEO` ｜ `流量实证`

以高流量站点为样本、用站内未做优化的页面作同期对照，基于一方分析与服务器日志剥离 ChatGPT 平台自身增长的“顺风”，量化 AEO 干预对引荐流量的真实增量，纠正公开案例中的增长倍数幻觉。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2606.04362) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 31. Assessing Web Search Credibility and Response Groundedness in Chat Assistants

*Ivan Vykopal 等（Brno University of Technology / Kempelen Institute）· EACL 2026 · 22 页* ｜ `可信度` ｜ `事实核查`

围绕五个易滋生错误信息的主题、100 条声明评估 GPT-4o、GPT-5、Perplexity、Qwen Chat 的信源可信度与答案接地性，发现各助手差异明显，部分模型在敏感话题上更常引用低可信来源。

- 🔗 [原文链接 ↗](https://aclanthology.org/2026.eacl-long.115/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 32. Do AI Overviews Benefit Search Engines? An Ecosystem Perspective

*Yihang Wu 等（Zhejiang University）· arXiv 预印本 · 2026 · 83 页* ｜ `生态博弈` ｜ `商业影响`

用博弈论模型刻画创作者的 costly effort 竞争，证明 AI Overviews 分流流量可能打击高质量供给、损害搜索引擎长期利润，并设计引用机制与补偿机制两类激励方案，基于真实点击数据验证可改善生态。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2601.22493) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)


## 四、安全、操纵与治理（7）

### 33. Ranking Manipulation for Conversational Search Engines

*Samuel Pfrommer, Yatong Bai 等（UC Berkeley）· EMNLP 2024 · 30 页* ｜ `提示注入` ｜ `排名操纵`

研究提示注入对对话式搜索引擎信源排序的影响，构建真实消费品网站数据集并将排序形式化为对抗问题，展示恶意注入字符串如何改变模型对产品名、正文内容与上下文位置的优先级。

- 🔗 [原文链接 ↗](https://aclanthology.org/2024.emnlp-main.534/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 34. Adversarial Search Engine Optimization for Large Language Models

*Fredrik Nestaas, Edoardo Debenedetti, Florian Tramèr（ETH Zurich）· ICLR 2025 · 32 页* ｜ `对抗攻击` ｜ `排名操纵`

提出“偏好操纵攻击”：精心构造的网页或插件文档可诱导 LLM 抬高攻击者产品、贬低竞品，并在 Bing、Perplexity 生产引擎与 GPT-4、Claude 插件 API 上验证，指出这会引发各方互害的囚徒困境。

- 🔗 [原文链接 ↗](https://openreview.net/forum?id=hkdqxN3c7t) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 35. Manipulating LLMs for Product Visibility: A Preliminary Analysis

*arXiv 预印本 · 2024 · 13 页* ｜ `内容操纵` ｜ `电商场景`

用虚构咖啡机目录做对照实验，证明在产品信息页植入精心设计的“策略文本序列（STS）”能显著提升其被 LLM 列为首选推荐的概率，揭示商品可见性可被低成本操纵。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2404.07981) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 36. The Ranking Blind Spot: Decision Hijacking in LLM-based Text Ranking

*Yaoyao Qian 等（Northeastern / Oregon State / 澳门大学）· EMNLP 2025 · 11 页* ｜ `决策劫持` ｜ `排名操纵`

揭示 LLM 多文档比较中的“排名盲点”，并演示决策目标劫持与决策标准劫持两类方式：内容方可诱导 LLM 排序器偏离评价目标、把特定文本排到首位。

- 🔗 [原文链接 ↗](https://aclanthology.org/2025.emnlp-main.1116/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 37. GRADA: Graph-based Reranking against Adversarial Documents Attack

*Jingjie Zheng 等（Melbourne / Edinburgh / Amazon）· EMNLP 2025 · 23 页* ｜ `防御方法` ｜ `RAG 安全`

针对对抗文档“语义贴近查询却偏离正常文档”的特征，提出基于图重排的 GRADA 防御框架，在六个大模型上显著降低对抗文档攻击成功率，同时保持正常检索质量。

- 🔗 [原文链接 ↗](https://aclanthology.org/2025.emnlp-main.1132/) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 38. Position: GEO Creates Underexamined Risks, Governance Must Target Concentration, Disclosure, and Academic Blind Spots

*Yizhu Wen, Nan Zhang 等 · ICML 2026 Position · 15 页* ｜ `立场论文` ｜ `治理`

立场论文梳理从 SEO 到 GEO 迁移中的风险：低可竞争性与系统敏感性造成的影响力集中、证据与推理中未披露的商业影响，以及学术实验与部署系统之间的评估盲区，呼吁答案层治理、高精度披露与黑盒审计。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2606.12439) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

### 39. Search Engines in the AI Era: A Qualitative Understanding of the False Promise of Factual and Verifiable Source-Cited Results

*Pranav Narayanan Venkit 等（Penn State / Salesforce AI Research）· FAccT 2025 · 16 页* ｜ `伦理` ｜ `质性研究`

对 21 名专家用户开展质性研究，对比答案引擎与传统搜索，归纳出“带引用即可信”假象背后的 16 项伦理与社会局限，反思来源引用式回答在事实性与可验证性上的虚假承诺。

- 🔗 [原文链接 ↗](https://doi.org/10.1145/3715275.3732089) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)


## 五、中文译文与导读（1）

### 40. GEO：生成式引擎优化（GEO 奠基论文 · 中文译文）

*Pranjal Aggarwal 等（IIT Delhi / Princeton）· 中英对照译文 · 24 页* ｜ `中文译文` ｜ `奠基论文`

GEO 奠基论文的中文译文与导读版本，便于中文读者理解生成式引擎优化的问题定义、九类可见性策略与核心实验结论；译文为学习材料，不等同于中文原创论文。

- 🔗 [原文链接 ↗](https://arxiv.org/abs/2311.09735) ｜ 📄 [飞书书库页（封面卡片 · PDF 附件）](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd)

---

*本页为 OpenGEO 书库编目索引，同步自飞书知识库 · [飞书书库页](https://larkcommunity.feishu.cn/wiki/L1rmwFbWKiLzPzkaxGIcoIh2nXd) · 第三方论文与报告版权归原作者及原机构所有，本页仅提供题录、摘要与公开来源链接。*
