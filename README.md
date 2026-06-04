# CAA-X: Cognitive Architecture eXtension

> **Author:** 鹿琦 / Lu Qi  
> **Affiliation:** Intellisia Institute (海国图智研究院)  
> **Preprint DOI:** [10.5281/zenodo.20502731](https://doi.org/10.5281/zenodo.20502731)  
> **Date:** 2026-06-02 (Last updated: 2026-06-03)

---

## 核心定位

CAA-X 是回应 LeCun 零样本 Agent 挑战的意图驱动认知架构框架，提供超越 Transformer 和 Post-Transformer 的元架构设计。

**核心问题：** 当前AI架构缺乏原生意图表示，导致多轮交互可靠性退化（39%）、输出同质化（"人工蜂群思维"）、零样本物理推理失败。

**核心论点：** 意图不是外部优化的产物，而是架构层面的构成性能力。

---

## 五个核心创新

| 组件 | 核心贡献 | 数学工具 |
|------|---------|---------|
| **1. 认知原子** | 弱耦合功能原语 + 持久性语义（ephemeral/durable/permanent） | 临界初始化、幂律雪崩 |
| **2. CML 2.0** | 三层可微符号系统（Latin/Semantic/Intentional） | Hamacher t-范数、能量基约束 |
| **3. GWP 协议引擎** | 协议层 vs 实现层 + 选择性同步 | 三层协议（Handshake/Competition/Broadcast） |
| **4. 认知流形** | 意图偏置测地线 + 元认知调度器 | 黎曼几何、随机微分方程 |
| **5. λ-序参量** | 五维可测量认知相变指标 | 信息几何、Landau-Ginzburg 理论 |

---

## 2026 前沿研究支撑

- ✅ **神经符号AI主流化** — Stanford AI Index 2026 合法化；Tufts 大学能耗降100倍
- ✅ **机制可解释性突破** — MIT 2026十大技术；SAE 显微镜揭示数百万可解释特征
- ✅ **组合性学习涌现** — ICML 2026 专题；Assign and Add 证明组合泛化是内部涌现
- ✅ **GWT 操作化** — Tait et al. (2026) 6个可测试标记；TPA 框架分布式整合
- ✅ **临界初始化生物学** — Pachitariu et al. (Nature 2026) 生物神经网络临界状态

---

## 文件导航

### 论文
- [完整论文 PDF](papers/CAA-X_V4_Full_Paper.pdf) — V4 完整版（44,177字符 / 773行 / 7章）
- [中文版本](papers/CAA-X_V4_CN.md) — 完整中文译文

### 理论配套文档
- [术语对齐表](docs/03_terminology_alignment.md) — CAA-X 术语与前沿研究的精确映射
- [实验验证路线图](docs/04_empirical_roadmap.md) — 短期/中期/长期三阶段验证计划
- [2026前沿动态整合](docs/05_recent_advances_2026.md) — 6月2-3日AI顶刊动态去重整合
- [可证伪预测扩展](docs/06_falsifiable_predictions_expanded.md) — 原19项 + 新增10项预测

### 代码与数据
- [更新版参考文献](bib/references_updated.bib) — 50+条 BibTeX（含2026新增）
- `code/` — 待上传（lambda分配器、GWP协议、认知流形原型）
- `data/` — 待上传（实验数据、基准测试结果）

---

## 快速开始

### 阅读路径

**路径A：快速概览（30分钟）**
1. 阅读本 README
2. 浏览 [术语对齐表](docs/03_terminology_alignment.md)
3. 查看 V4 论文摘要和目录

**路径B：深度理解（3小时）**
1. 阅读 [2026前沿动态整合](docs/05_recent_advances_2026.md)
2. 精读 V4 论文第1-3章（引言、认知原子、GWP）
3. 查看 [实验验证路线图](docs/04_empirical_roadmap.md)

**路径C：批判性评估（1天）**
1. 完整阅读 V4 论文
2. 逐项检查 [可证伪预测](docs/06_falsifiable_predictions_expanded.md)
3. 对比现有工作（JEPA、WAMs、GNWT-Agent）

### 引用

```bibtex
@misc{lu2026caax,
  author       = {Lu, Qi},
  title        = {CAA-X: Cognitive Architecture eXtension for Zero-Shot Agent Challenges},
  year         = {2026},
  doi          = {10.5281/zenodo.20502731},
  url          = {https://github.com/leodarc/CAA-X},
  institution  = {Intellisia Institute}
}
```

---

## 与现有工作的关系

| 现有工作 | CAA-X 定位 | 关键差异 |
|---------|-----------|---------|
| **LeCun JEPA** | 预测性架构 | CAA-X 增加意图层和 λ-序参量 |
| **WAMs (复旦)** | 世界动作模型 | CAA-X 提供认知架构的工程实现 |
| **GNWT-Agent** | GWT 实现 | GWP 是协议而非功能架构，支持跨系统互操作 |
| **MIRROR** | GWT 增强 LLM | GWP 动态 λ 分配 vs MIRROR 固定注意力权重 |
| **anima-kernel** | 开源 GWT | GWP 显式协议规范 vs 隐式事件驱动 |
| **AgentSquare** | 模块化搜索 | CAA-X 提供理论框架，AgentSquare 是系统级验证 |

---

## 社区与贡献

- **讨论区:** [GitHub Discussions](https://github.com/leodarc/CAA-X/discussions)
- **问题报告:** [GitHub Issues](https://github.com/leodarc/CAA-X/issues)
- **邮件联系:** [待补充]

### 贡献指南

欢迎以下形式的贡献：
- 预测验证实验（见 [路线图](docs/04_empirical_roadmap.md)）
- 术语对齐补充（见 [术语表](docs/03_terminology_alignment.md)）
- 代码实现（lambda分配器、GWP协议、认知流形）
- 翻译与传播

---

## 许可证

[CC BY 4.0](LICENSE) — 允许自由使用、修改、分发，需署名原作者。

---

## 版本历史

| 版本 | 日期 | 变更 |
|------|------|------|
| V4 | 2026-06-02 | 完整论文发布，含7章、16定理、3算法、19预测 |
| V4.1 | 2026-06-03 | 新增术语对齐表、实验路线图、前沿动态整合、预测扩展、参考文献更新 |

---

*CAA-X 是神经符号AI时代的标准认知架构参考模型。*
