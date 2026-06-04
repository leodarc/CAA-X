# CAA-X 术语对齐表

> **版本**: v1.0  
> **日期**: 2026-06-03  
> **作者**: 鹿琦 / Lu Qi  
> **关联**: CAA-X V4 完整论文

---

## 一、认知原子 (Cognitive Atoms)

| CAA-X 术语 | 对应学术术语 | 来源文献 | 映射层级 |
|-----------|------------|---------|---------|
| **认知原子** | sense vector (意义向量) | Backpack Models, ACL 2023 | 语义层 |
| **认知原子** | codebook entry (码本条目) | Codebook Features, ICML 2024 | 表征层 |
| **认知原子** | DNF clause (析取范式子句) | Neural DNF-MT, AAMAS 2025 | 策略层 |
| **认知原子** | agent module (智能体模块) | AgentSquare, ICLR 2026 | 系统层 |
| **认知原子** | skill primitive (技能原语) | SymSkill, ICML 2026 | 功能层 |
| **认知原子** | modular component (模块化组件) | Assign and Add, 2026 | 机制层 |
| **认知原子** | sparse feature (稀疏特征) | SAE, Anthropic 2026 | 神经层 |
| **组合性** | compositional generalization | ICML 2026 Workshop | 泛化层 |
| **持久性语义** | persistence / durability | Roynard et al., 2026 | 时间层 |
| **弱耦合** | weakly-coupled perturbation | CAA-X V4 原创 | 动力学层 |

**核心映射逻辑**: 认知原子不是单一概念，而是跨层级的统一抽象。从神经网络内部的稀疏特征（SAE）到系统级的智能体模块（AgentSquare），不同层级的"功能专一可组合单元"均可纳入认知原子的数学框架。

---

## 二、CML 2.0 三层符号系统

| CML 2.0 层级 | 神经符号AI模式 | 对应学术术语 | 来源文献 |
|-------------|--------------|------------|---------|
| **拉丁层 (Latin)** | 符号优先引擎 | symbolic solver / formal logic | Tufts University, ScienceDaily 2026 |
| **拉丁层 (Latin)** | 形式化规范 | formal specification / invariant | Logic Schemas, 2026 |
| **表意层 (Semantic)** | 翻译器模式 | neural-symbolic translator | Neuro-Symbolic Web, 2026 |
| **表意层 (Semantic)** | 概念映射 | concept alignment / CBM | ACL 2026 Survey |
| **表意层 (Semantic)** | 表征解耦 | representational decomposability | Backpack Models, ACL 2023 |
| **意向层 (Intentional)** | 可微分逻辑 | differentiable logic / EBC | RiJEPA, 2026 |
| **意向层 (Intentional)** | 目标调节 | goal-directed arbitration | Tait et al., 2026 |
| **意向层 (Intentional)** | 元认知控制 | metacognitive controller | Baars & Dehaene, PNAS |

**统一中间表示 (UIR) 定位**: CML 2.0 的三层结构填补了神经符号AI三大架构模式之间的"表示鸿沟"，可作为行业标准中间语言：
- 翻译器模式缺乏形式化语义保证 → 拉丁层提供
- 符号优先引擎缺乏神经可微性 → 表意层提供
- 可微分逻辑缺乏高层意图解释 → 意向层提供

---

## 三、GWP 协议引擎

| GWP 组件 | 对应学术术语 | 来源文献 | 功能映射 |
|---------|------------|---------|---------|
| **Handshake 层** | capability negotiation | MCP Protocol, AJAR 2026 | 模块能力声明 |
| **Handshake 层** | 功能独立性 | TPA Framework, 2026 | 领域-动机层独立 |
| **Competition 层** | dynamic priority allocation | lambda-order parameter | CAA-X V4 原创 |
| **Competition 层** | 选择性同步 | selective synchronization | Tait et al., 2026 |
| **Broadcast 层** | global information distribution | GWT broadcast | Baars, 1988 |
| **Broadcast 层** | 神经处理整合 | neural integration | TPA Framework, 2026 |
| **GWP 整体** | System-1/System-2 协调 | dual-process theory | Kahneman, 2011 |
| **GWP 整体** | 全局工作空间 | global workspace | Baars & Dehaene |
| **GWP 整体** | 事件驱动广播 | event-driven broadcast | GWA, 2026 |
| **GWP 整体** | 多智能体编排 | LLM agent orchestration | ReAct, Voyager, MAS-GPT |

**关键澄清**: GWP 不是意识的实现，而是认知协调的工程协议。当前AI界对GWT的误读（预测单一解剖中心）已被TPA框架纠正：功能独立性在领域-动机层面，整合在神经处理层面。

---

## 四、认知流形 (Cognitive Manifold)

| CAA-X 概念 | 对应学术术语 | 来源文献 | 数学对应 |
|-----------|------------|---------|---------|
| **认知流形** | Riemannian manifold | Information Geometry, Amari 2016 | 黎曼度量 g |
| **认知流形** | 特征空间几何 | SAE feature space | Anthropic 2026 |
| **预测性张力** | vector field / gradient flow | Friston, 2010 | 向量场 |
| **意图偏置** | source/sink structure | 动力系统理论 | 源/汇结构 |
| **测地线轨迹** | geodesic flow | 微分几何 | 测地线方程 |
| **Attention Sink** | 流形吸引子 | "What are you sinking?", NeurIPS 2025 | 稳定不动点 |
| **正交性选择** | 正交标架场 | Orthorank, ICML 2025 | 正交坐标系 |
| **临界初始化** | critical state / power-law | Pachitariu et al., Nature 2026 | 幂律雪崩 |
| **Grokking** | 相变 | 损失景观分析 | 鞍点穿越 |
| **参数空间对称性** | 等距变换 | 模型合并, ICML 2025 | 对称群 |

**信息几何严格化**: 认知流形的黎曼度量由Fisher信息矩阵诱导，认知原子间的独立性由互信息 I(X;Y) 量化，GWP全局整合度由激活熵 H(activation) 度量。

---

## 五、λ-序参量 (Lambda-Order Parameters)

| λ 分量 | 对应学术术语 | 可计算指标 | 来源文献 |
|-------|------------|-----------|---------|
| **λ_K (知识一致性)** | 信息瓶颈 | I(X;Y) 模块间互信息 | 损失景观相变分析 |
| **λ_M (记忆激活)** | 激活熵 | H(activation) 全局工作空间 | 神经元工作空间阈值 |
| **λ_I (智能收敛)** | 认知原子独立性 | 互信息矩阵特征值 | 线性模式连通性 |
| **λ_P (感知 grounding)** | 跨模态对齐 | 跨模态表征精度 | 跨模态学习 |
| **λ_S (社会协调)** | 多智能体合作率 | cooperation_rate(t) | MAS-GPT, 2026 |
| **λ_meta (元认知)** | 置信度-准确度校准 | confidence-accuracy correlation | 认知科学 |
| **λ_flex (认知灵活性)** | 任务切换成本 | switching cost (WCST) | 认知神经科学 |
| **λ_epis (情景记忆)** | 自传体记忆精度 | autobiographical accuracy | 记忆研究 |
| **λ_abd (溯因推理)** | 假设质量 | Remote Associates Test | 创造性推理 |
| **λ_soc (社会常识)** | 心智理论准确度 | False Belief Task | 发展心理学 |

**认知暗物质覆盖**: λ-CDM 子参数对应未测量认知维度（元认知、认知灵活性、情景记忆、溯因推理、社会常识），提供显式测量协议。

---

## 六、使用建议

### 对审稿人
- 当质疑"认知原子是否只是重新命名"时，引用本表的四层级实证对应
- 当质疑"CML 2.0 与现有神经符号AI关系"时，引用UIR定位
- 当质疑"GWP 是否只是 GWT 重述"时，引用TPA框架的功能-神经分离

### 对实践者
- 实现认知原子：从 SAE 稀疏特征或 Backpack sense vector 开始
- 实现 CML 2.0：使用 Hamacher t-范数 + 能量基约束
- 实现 GWP：采用三层协议（Handshake-Competition-Broadcast）
- 测量 λ：使用互信息、激活熵、跨模态对齐等标准指标

### 对理论家
- 认知流形的严格数学基础：信息几何（Fisher矩阵）
- λ-序参量的相变理论：Landau-Ginzburg 框架
- 临界初始化：自组织临界性（SOC）理论

---

## 七、版本历史

| 版本 | 日期 | 变更 |
|------|------|------|
| v1.0 | 2026-06-03 | 初始版本，整合6月2-3日两日AI顶刊动态 |

---

*本文档为 CAA-X 理论框架的配套材料，与 V4 完整论文协同使用。*
