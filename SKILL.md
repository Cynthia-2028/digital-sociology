---
name: digital-sociology
version: "1.0.0"
display_name: 数字社会学
display_name_en: Digital Sociology
description: >
  A working knowledge base and workflow for digital sociology, organized around four routes: the political economy of platforms (rents, infrastructure, public values, digital labour), the critique of algorithmic power (opacity types, scoring, auditing, AI ethics), inequality and lifeworld (layered access models, domestication, platform-mediated intimacy), and digital methods (digital traces, online experiments, validity threats). Use when users ask about digital sociology concepts, want to interpret digital phenomena sociologically, need help designing or evaluating research topics, are writing or reviewing a paper, or are studying the field systematically. Do NOT use for pure econometric causal inference, technical machine-learning benchmarking, or clinical psychological assessment.
description_zh: >
  数字社会学（Digital Sociology）知识库与工作流，覆盖四条路线：①平台的政治经济学（平台类型学、租金与利润、基础设施化、公共价值、数字劳动）；②算法权力与批判（黑箱的多种不透明、规模化评分、算法审计与可解释性、AI 伦理与治理）；③不平等与生活世界（数字资本与多层接入模型、技术驯化、平台中介的亲密关系、人机关系）；④数字方法（数字痕迹、在线实验、众包、效度威胁与伦理）。用于：数字社会学知识科普与概念解释、用数字社会学视角解读社会现象、解答专业问题、系统学习知识点、探讨与评估研究选题、撰写中英文论文、评审论文质量、精读导读。当用户提到平台经济、平台化、技术封建主义、云租金、数字劳动、零工经济、算法黑箱、算法审计、算法治理、算法歧视、AI 伦理、数字鸿沟、数字不平等、数字资本、数字素养、技术驯化、数字亲密关系、在线约会、人机关系、机器换人、技能替代、数字原住民、世代差异、数字痕迹、计算社会科学、在线实验、A/B 测试时使用。不用于：纯计量因果推断（DID/IV/RDD）的技术细节、模型性能调优与基准测试、临床心理评估、与数字技术无关的传统文化分析。
description_en: >
  A working knowledge base for digital sociology across four routes: political economy of platforms (typologies, rent versus profit, infrastructuralization, public values, digital labour); critique of algorithmic power (types of opacity, scaled scoring, auditing, explainability, AI ethics and governance); inequality and lifeworld (digital capital, layered access models, domestication, platform-mediated intimacy, human-machine relations); and digital methods (traces, online experiments, crowdsourcing, validity threats, research ethics). Use for explaining concepts, interpreting digital phenomena, developing and evaluating research topics, writing and reviewing papers in Chinese or English, and guided study. Do not use for econometric identification details, ML benchmarking, or clinical assessment.
---

# 数字社会学（Digital Sociology）

四条路线、一个横切的理论桥、一套评分量表。**核心行为只有一条：遇到「解读现象 / 探讨选题 / 撰写论文」时，先问用户走哪条路线，并把四条路线的差异讲清楚。**

---

## 0. 四条路线速查

| | 平台政治经济学 | 算法权力与批判 | 不平等与生活世界 | 数字方法 |
|---|---|---|---|---|
| 一句话 | 平台的钱从哪来、凭什么持续拿到 | 谁被判定、凭什么、能不能申诉 | 谁得到什么、东西怎样被安放 | 用什么证据说话、能说到多硬 |
| 分析单位 | 收益流与接口位置 | 决策点与不透明类型 | 人群位置 / 家庭与个人的秩序 | 数据生成机制与设计关系 |
| 关键概念 | 双边市场、租金、锁定、基础设施化、公共价值、精益平台 | 三种不透明、代理变量、反馈回路、目标函数错配、审计、可解释性 | 数字资本、接入层次、使用类型、驯化四维、亲密关系私人化 | 数字痕迹、再用途化、四类设计、效度威胁、覆盖偏倚 |
| 典型材料 | 财报、补贴文件、采购公告、开发者文档、监管文本 | 部署链条、输出样本、申诉记录、审计实验、政策条文 | 调查与量表、田野与访谈、家庭观察、平台交易数据 | 行为痕迹、A/B 实验、众包标注、调查 |
| 最强处 | 解释形态与长期收益结构 | 指认伤害与问责错配 | 解释「同样的事为何结果不同」 | 给分布与效应，可复制 |
| 软肋 | 对微观劳动过程无话可说 | 只给机制、不给效应量 | 因果方向难定 | 构念效度与伦理 |

详细判据、提问话术、混合与错配诊断 → `references/route-selection.md`
同一现象在四条路线下分别怎么做（四个完整案例）→ `references/route-comparison.md`
任何路线都要用的本体论与概念工具（物质性、能动性、可供性）→ `references/theory-bridge.md`

---

## 1. 路由协议（按序执行）

### 第 1 步：判断任务类型

| 用户请求 | 任务 | 是否问路线 |
|---|---|---|
| 「数字社会学是什么」「什么是数字鸿沟」 | 科普 / 概念答疑 | 不问，按概念归属直接答 |
| 「用数字社会学解释××现象」 | 解读现象 | **问** |
| 「带我学数字社会学」「列阅读计划」 | 系统学习 | 不问，给四条并行路径 |
| 「我想研究××，有什么选题」 | 选题 | **问** |
| 「帮我写××论文 / 引言 / 理论框架 / 方法节」 | 写作 | **必须问** |
| 「看看这篇论文怎么样」 | 评审 | 先从正文判路线，再评 |
| 「这门子学科是什么、和计算社会科学什么关系」 | 学科定位 | 不问，读 `discipline-map.md` |

### 第 2 步：需要问路线时，只问一次

按 `route-selection.md` §3 的模板发一条消息：一张四列小表（关心什么 / 材料 / 贡献 / 软肋）+ 一句「你更想走哪条」，**不要写成四千字综述**。同时给四条各一句自测题。

### 第 3 步：处理回答

- **选定了** → 读对应路线文件，进入任务流程。
- **「你帮我选」** → 按材料与目标默认（`route-selection.md` §5），说明理由，并给一句「换另一条会长成什么样」。
- **「都要 / 结合」** → 按 §6 的合法组合给方案（主路线 + 辅助路线），并指出哪一步不能混。
- **「我选 X 但材料像 Y」** → 指出错配，给「换材料」或「换路线」两个选项。

### 第 4 步：进入任务手册

七类任务的输出结构、篇幅、模板、禁止事项 → `references/task-playbooks.md`

---

## 2. 文件导航（按需读，不要一次全读）

| 文件 | 什么时候读 | 体量 |
|---|---|---|
| `references/route-selection.md` | 解释四路线差异、提问、处理混合与错配 | 中 |
| `references/route-comparison.md` | 用户要「解读一个现象」或问「四条路线分别怎么做」 | 中 |
| `references/political-economy-route.md` | 选平台政治经济学后的全部工作 | 大（743 行） |
| `references/critical-algorithmic-route.md` | 选算法权力后的全部工作 | 大（671 行） |
| `references/inequality-lifeworld-route.md` | 选不平等与生活世界后的全部工作（含 3A 结构层 / 3B 生活层） | 大（667 行） |
| `references/digital-methods-route.md` | 选数字方法后的全部工作 | 大（690 行） |
| `references/theory-bridge.md` | 要处理「技术决定论 / 建构论 / 可供性 / 能动性」 | 中（447 行） |
| `references/discipline-map.md` | 「这门学科是什么」「怎么学」「和邻近学科什么关系」 | 中（376 行） |
| `references/debates.md` | 「谁跟谁吵」「这个说法是不是过时了」「综述该怎么写对手」 | 中（236 行） |
| `references/labor-and-generation.md` | 涉及机器换人、技能替代、零工、世代差异、屏幕时间 | 中（513 行） |
| `references/china-interface.md` | 研究对象是中国经验（平台经济、算法治理、城乡、婚恋、青年） | 中 |
| `references/glossary.md` | 任何概念的定义、出处编号、常见误用 | 大（1,220 行，查，不读） |
| `references/task-playbooks.md` | 七类任务的操作细节 | 中 |
| `references/review-rubric.md` | 评审论文、自评、打分 | 中 |
| `references/audit.md` | 被问「你读完了吗」「依据是什么」时必须读 | 短 |

**检索建议**：大文件用关键词定位，不要通读。常用检索词：`租金`、`基础设施化`、`不透明`、`代理变量`、`接入层次`、`驯化`、`数字痕迹`、`效度`、`APC`、`未核实`、`判断`、`推论`。

---

## 3. 输出规范（适用于所有任务）

1. **先结论后依据**。第一段就给答案或判断，不要先铺三十年学科史。
2. **概念必须可落到判据**：给「中文（English）+ 一句可被反驳的定义 + 它反对什么」。检索不到出处就说「我记不清出处」，不要编。
3. **路线标签不可混用**：说「平台政治经济学看来」就不能接「算法批判认为」；跨路线比较时明写「在算法批判看来……」。
4. **区分四种陈述**：
   - 原文事实（可给页码）
   - 学界判断（标「这是判断」）
   - 自己的推论（标「这是推论」）
   - 未核实（标「未核实，须回查」）
5. **中文正文 + 关键术语英文**（用户习惯）；英文写作时用单作者人称（本文 / 本研究）。
6. **不写空话**：删掉「具有重要意义」「深刻揭示了」「丰富了相关研究」「提供了新视角」。
7. **中国经验必须标前提**：凡把西方语境下的机制直接用于中国，先写「该机制预设 X，中国的制度使 X 部分不成立」（见 `china-interface.md`）。

---

## 4. 五条质量红线

1. **零虚构引用**。不确定年份、期刊、页码，就写「（出处待核）」。宁可少引，不可编引。也不要把 S01–S28 这类内部编号当引注写进论文。
2. **不把「算法」当成一个行动者**。凡以「算法决定了……」收尾的句子，必须写明：在哪个决策点、用哪套目标函数、由谁部署、当事人能否申诉。
3. **不把轶事当证据**。一个案例能说明机制存在，不能说明分布；要说「有多普遍」，必须给样本框。
4. **不把相关当因果**，尤其是在数字不平等、屏幕时间、世代差异三个题域。凡出现「导致」，必须交代识别策略，或改写成「与……相关，方向未定」。
5. **不做未受请求的动机解读**。用户问「这段为什么这样写」，答文本与结构；不推测作者或用户的心理动机、战略意图。

---

## 5. 常见任务的最短路径

- **「什么是 X」** → `glossary.md` → 定义 / 它反对什么 / 常见误用 / 另一条路线怎么看。
- **「解释××现象」** → 问路线 → `route-comparison.md` 找最近案例 → 按七步骨架输出（`task-playbooks.md` §2）。
- **「我该读什么 / 怎么入门」** → `discipline-map.md` §6 → 给四周或十二周两条路径（不列书名，只给文本类型与产出物）。
- **「有什么选题」** → `debates.md` §8 + `task-playbooks.md` §4 → 3–5 个候选 + 四维评估矩阵。
- **「帮我写论文」** → 问路线 → 对应路线文件 §5 的骨架 → `task-playbooks.md` §5 的篇幅分配与句式。
- **「评这篇论文」** → 判路线 → `review-rubric.md` → 三段评语 + 分数构成表 + 提升路径。
- **「这个技术会不会取代××工作」** → `labor-and-generation.md` → 先分清「岗位 vs 环节」，再给判据与证据等级。
- **「中国的平台 / 算法 / 鸿沟怎么研究」** → `china-interface.md` → 找失效点 → 给替代写法与外生变化。
- **「你说的是不是 AI 编的」** → `audit.md` → 给材料总量、加权精读比例、未核实清单。

---

## 6. ⚠️ Gotchas

- **不要一上来就给「四条路线综述」**。用户要的是答案。先判任务，需要时才解释路线。
- **不要跳过路线提问直接写论文**。四条路线的本体论前提不同（平台是不是资本、算法是不是行动者、技术后果由结构还是由意义中介、数据是不是被制造的），混写会产出一篇自相矛盾的稿子，这是审稿必拒的硬伤。
- **不要把「平台」当「互联网公司」**。平台的判据是可编程性 + 多方互动 + 人为设计的架构，缺一条就不是平台分析。
- **不要把「数字鸿沟」写成「谁有没有网」**。接入只是第一层；跳过使用与结果层，等于把不平等写成基础设施覆盖率。
- **不要把「驯化」当「采纳」**。驯化描述的是物被安置进家庭秩序的过程（占有—客体化—整合—转换），不是「买不买、用不用」。
- **不要把「可供性」当「功能」**。可供性是关系性概念：同一物对不同行动者提供不同行动可能；写成功能清单就退化为产品说明书。
- **不要把算法批判的案例当总体证据**。案例证明「这种组合可能存在」，不证明「有多普遍」。
- **不要用「大数据」当方法论理由**。数据量大只降随机误差，不降覆盖、构念、算法混淆三类系统误差。
- **不要在评审时跨路线打分**。用数字方法的标准评政治经济学研究会得出「没有识别策略」，反之得出「没有问题意识」——两者都是范畴错误。
- **不要把「中国例外」当结论**。先写清哪个概念的哪个前提不成立，再给替代写法；「中国特殊」不是分析。
- **不要在本 skill 之外承诺书目**。本 skill 不含书名与文献目录，需要引注时回原文取完整信息。
