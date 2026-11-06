# 单点GPU智算中心算电协同优先文献20篇

筛选日期：2026-10-15。中文标题为译名。范围为 Applied Energy 与 Energy，延续检索链接的2024—2027年范围。此表根据定向检索可获取的题名、摘要和Highlights整理，未完整逐篇审阅原结果页242篇。

研究基准来自 20260917-20260924/文件/Q.docx：大型单点GPU智算中心，自建风光装机已定，电网兜底；以年度化综合能源成本最小为目标，联合优化任务时序、储能功率与容量、充放电；关注SLA、动态PUE、储能退化与绿电约束。

排序依据是对任务建模、绿电直连、储能替代价值、冷却耦合和实验设计的可用程度。前10篇优先精读，11—16按建模问题补充，17—20按方法扩展选读。已有总结5篇，其余15篇在检查的52份可读DOCX/PPTX/MD/TXT文件中未命中完整英文题名；这不等于从未读过或本地没有PDF。

## 1 考虑计算资源动态池化的算力中心微电网协同调度优化

**Coordinated scheduling optimization for Computility center microgrid considering computing resources dynamic pooling**

期刊：Applied Energy；年份：2025；本地状态：已有明确总结。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261925007019) · [DOI](https://doi.org/10.1016/j.apenergy.2025.125971)

研究侧重点：将异构工作负载、CPU/GPU核心占用和计算资源池化接入光伏微电网协同调度。

对本研究的用途：借鉴任务—资源—功率映射，以及有无任务调度、有无储能的对照设计。

适用边界：其资源池化假设应结合你的GPU整卡或多卡任务约束调整。

已有总结位置：D:\XMUT\tsingHua\调研\20261008-202610\论文调研.docx

## 2 绿电直连数据中心风—光—储—网系统综合规划

**Integrated planning of wind–solar–storage–grid systems for private-wire supplied data centers**

期刊：Applied Energy；年份：2026；本地状态：已有明确总结。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926004939) · [DOI](https://doi.org/10.1016/j.apenergy.2026.127841)

研究侧重点：风光、储能功率和容量、并网交换及专线可输送能力的联合规划，考虑全年逐时运行与气候驱动PUE。

对本研究的用途：支撑你的绿电直连系统边界、逐时电量平衡、储能功率/容量和年化成本建模。

适用边界：该文还优化选址和风光容量；你的方案中风光装机已定，可固定这些变量。

已有总结位置：D:\XMUT\tsingHua\调研\20260909-20260916\Integrated planning of wind–solar–storage–grid systems for private-wire.docx

## 3 基于最优能耗特性的数据中心负荷建模 同时提升能源效率与需求响应质量

**Data center load modeling through optimal energy consumption characteristics: A path to simultaneously enhance energy efficiency and demand response quality**

期刊：Applied Energy；年份：2025；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261925008256) · [DOI](https://doi.org/10.1016/j.apenergy.2025.126095)

研究侧重点：建立计算、冷却、供配电之间的电—热—性能模型，并提取较简化的负荷模型。

对本研究的用途：支撑任务级GPU调度到设施总负荷的转换，并帮助评估线性负荷模型的误差。

适用边界：通用数据中心模型，GPU任务部分仍需专门标定。

## 4 基于AI任务拆分与分配的数据中心低碳及服务质量感知运行

**Low-carbon and QoS-aware operation of data centers by AI task splitting and allocation**

期刊：Applied Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261925018628) · [DOI](https://doi.org/10.1016/j.apenergy.2025.127132)

研究侧重点：通过AI任务拆分和分配调整资源需求与执行时长，并进行低碳、QoS感知在线调度。

对本研究的用途：借鉴AI任务资源需求、时限和可调度性建模，明确任务移到绿电时段的可行条件。

适用边界：任务可拆分性需要验证；拆分策略属于你现有方案的扩展选项。

## 5 考虑算电耦合运行和供需不确定性的数据中心集群综合能源容量配置双层规划

**A bi-level planning model of integrated energy capacity configuration for data center cluster considering computing-electricity coupling operation and supply-demand uncertainties**

期刊：Applied Energy；年份：2026；本地状态：已有明确总结。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926011554) · [DOI](https://doi.org/10.1016/j.apenergy.2026.128499)

研究侧重点：将设备容量配置、计算任务调度和供需不确定性联合纳入双层规划。

对本研究的用途：支撑储能配置—任务调度的联动框架，并参考计算柔性与实体储能之间的替代关系。

适用边界：对象是多中心集群且含CCHP等设备；可提取单点储能与任务调度部分。

已有总结位置：D:\XMUT\tsingHua\调研\20261008-202610\论文调研.docx

## 6 数据中心全要素灵活性资源综合评估 考虑算力、电力与热力协同收益

**Comprehensive evaluation of all-element flexibility resources in data centers: considering synergistic benefits of computing, electricity, and heat**

期刊：Applied Energy；年份：2025；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261925011729) · [DOI](https://doi.org/10.1016/j.apenergy.2025.126442)

研究侧重点：联合刻画计算、电和热的灵活性，评估成本、能耗、碳排及PUE等变化。

对本研究的用途：设计任务柔性、储能和热侧柔性的独立及联合对照，量化各部分贡献。

适用边界：多目标评价指标可参考；你的主目标仍可保持年度化综合成本最小。

## 7 数据中心工作负载与能源系统一体化管理

**Integrated management of workloads and energy system for data centers**

期刊：Energy；年份：2025；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0360544225020420) · [DOI](https://doi.org/10.1016/j.energy.2025.136400)

研究侧重点：在单个数据中心内联合优化异构工作负载转移与能源调度，分析成本与任务延迟的权衡。

对本研究的用途：支撑SLA约束和任务延迟统计，避免只报告省电费而遗漏服务代价。

适用边界：其工作负载模型需按你的GPU任务数据改写。

## 8 能源系统灵活性供给及设计运行对数据中心可靠性的定量影响与关键参数

**Quantitative impacts of energy system flexibility provision and design/operation on data center reliability and the key influential parameters**

期刊：Applied Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926005568) · [DOI](https://doi.org/10.1016/j.apenergy.2026.127904)

研究侧重点：从全寿命周期考虑电池退化、备用与调节双重用途及供电可靠性。

对本研究的用途：支撑储能退化和备用约束，检查为追求经济性而调用电池对可靠性的影响。

适用边界：以能源系统可靠性分析为主，计算任务柔性需要与你的模型衔接。

## 9 挖掘数据中心支撑智能电网服务的灵活性 渐进式负载下储能优化调度与设计

**Unlocking the flexibilities of data centers for smart grid services: Optimal dispatch and design of energy storage systems under progressive loading**

期刊：Energy；年份：2025；本地状态：已有明确总结。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0360544225001537) · [DOI](https://doi.org/10.1016/j.energy.2025.134511)

研究侧重点：在应急保障约束下研究电池与蓄冷储能的富余容量利用、运行和投资方案。

对本研究的用途：借鉴储能成本年化、备用容量和容量配置—运行收益的联合比较。

适用边界：负载渐进增长和辅助服务收益属于该文特定场景；应按你的业务边界选用。

已有总结位置：D:\XMUT\tsingHua\调研\20261008-202610\论文调研.docx

## 10 提升数据中心能源效率 面向电力、计算与冷却一体化管理的最优任务调度

**Enhancing data center energy efficiency: Optimal workload scheduling for integrated power-computing-cooling management**

期刊：Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S036054422601580X) · [DOI](https://doi.org/10.1016/j.energy.2026.141474)

研究侧重点：联合任务分配和冷却控制，描述环境、热负荷、变风量及分区效率差异。

对本研究的用途：直接支撑动态PUE或显式冷却功耗，研究任务追随午间光伏时的额外制冷成本。

适用边界：可先提取冷却功耗函数，详细风机控制是后续扩展。

## 11 数据中心蓄冷与IT工作负载迁移协同控制策略研究

**Research on collaborative control strategy of cold storage and IT workload migration in data center**

期刊：Energy；年份：2025；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0360544225014446) · [DOI](https://doi.org/10.1016/j.energy.2025.135802)

研究侧重点：利用模型预测控制联合任务时间转移、蓄冷与冷却设备运行，分析昼夜温差对PUE的影响。

对本研究的用途：回答任务时间转移如何改变冷却收益，并参考负荷移峰与储能协同的实验设计。

适用边界：其储能为蓄冷；电化学储能部分需另行建模。

## 12 面向成本最优的电力与计算联合管理 新型预测—优化框架

**Towards cost-optimal joint electricity-computation management: A novel predict-then-optimize framework**

期刊：Applied Energy；年份：2026；本地状态：已有明确总结。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926003867) · [DOI](https://doi.org/10.1016/j.apenergy.2026.127734)

研究侧重点：以最终联合调度成本来训练预测模型，考虑新能源和不同任务量的不确定性。

对本研究的用途：作为从确定性优化扩展到预测误差及滚动调度的参考，评价预测误差对年度成本的影响。

适用边界：包含电力系统与数据中心运营者协同；可先借鉴成本导向评价。

已有总结位置：D:\XMUT\tsingHua\调研\20261008-202610\论文调研.docx

## 13 基于数据驱动不确定性场景生成的电—热—算耦合数据中心双层规划

**Bi-level planning of data centers with coupled electricity-heat-computation system using data-driven scenario generation for representing uncertainties**

期刊：Applied Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926000218) · [DOI](https://doi.org/10.1016/j.apenergy.2026.127369)

研究侧重点：以生成场景描述运行不确定性，在双层规划中考虑设备配置、计算温度和储能风险。

对本研究的用途：参考容量配置与运行的衔接，以及全年运行数据、场景和不确定性的处理。

适用边界：使用较复杂的场景生成方法，可先用历史典型日实现基线。

## 14 液冷数据中心的需求响应潜力

**Exploring the Demand Response Potential of Liquid-Cooled Data Centers**

期刊：Applied Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926003314) · [DOI](https://doi.org/10.1016/j.apenergy.2026.127679)

研究侧重点：构建液冷数据中心电热耦合模型，协调服务器与液冷系统的需求响应。

对本研究的用途：适合液冷GPU智算中心的温度、冷却功耗与服务约束建模。

适用边界：液冷系统结构需要与你假设的机房条件一致。

## 15 基于解耦多层AI工作负载模型的电池储能与AI数据中心风险感知协同调度

**Risk-aware coordinated scheduling of battery storage and AI data centers with decoupled multi-layer AI workload models**

期刊：Applied Energy；年份：2027（期刊卷期）；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261926014923)

研究侧重点：利用真实GPU轨迹将AI工作负载映射为设施功率，并联合调度任务、储能和爬坡备用。

对本研究的用途：参考真实GPU负荷建模与任务—电池协调；对接网功率波动分析也有价值。

适用边界：主要解决分钟/秒级并网爬坡风险，时间尺度与年度储能配置不同。

## 16 考虑任务延迟容忍差异的数据中心性能成本优化高速REPTA算法

**High-speed REPTA algorithm for performance cost optimization in data centers considering workload delay tolerances**

期刊：Applied Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261925018860) · [DOI](https://doi.org/10.1016/j.apenergy.2025.127156)

研究侧重点：区分任务延迟容忍度，并以新能源与电价感知的任务分配策略提升调度求解效率。

对本研究的用途：参考逐任务SLA和异质时间窗口，避免全部可调任务采用相同延迟上限。

适用边界：原场景为地理分布式数据中心，单点模型只提取时间柔性部分。

## 17 微型数据中心绿色优化 面向综合能耗策略的任务调度

**Green optimization for micro data centers: Task scheduling for a combined energy consumption strategy**

期刊：Applied Energy；年份：2025；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0306261925007615) · [DOI](https://doi.org/10.1016/j.apenergy.2025.126031)

研究侧重点：联合服务器、冷却和自适应热控能耗进行任务调度，并采用强化学习求解。

对本研究的用途：参考完整设施能耗核算和任务调度基线，检查模型是否遗漏配套能耗。

适用边界：对象为微型数据中心，大型GPU集群应用需重新标定。

## 18 热感知任务调度与深度强化学习冷却控制的协同优化

**Co-optimization of thermal-aware workload scheduling with deep reinforcement learning-based cooling control in data centers**

期刊：Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0360544226000678) · [DOI](https://doi.org/10.1016/j.energy.2026.139965)

研究侧重点：联合热感知调度、温度预测和空调控制，在热安全约束下减少能耗。

对本研究的用途：借鉴温度约束及工作负载与冷却相互作用，作为冷却模型或控制方法的补充。

适用边界：更侧重运行控制，可在完成主优化模型后阅读。

## 19 数据中心任务调度与热环境的跨系统协同管理

**Cross-sector management for workload scheduling and thermal environment in data centers**

期刊：Energy；年份：2026；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S0360544226016142) · [DOI](https://doi.org/10.1016/j.energy.2026.141508)

研究侧重点：将IT工作负载与HVAC热环境纳入统一决策过程，优化双向耦合运行。

对本研究的用途：补充任务迁移如何改变热环境及冷却效率，完善动态PUE的建模依据。

适用边界：和第10、18篇主题相近，可按所选冷却建模深度择重点阅读。

## 20 兼顾运行经济性与可靠性的数据中心园区分布鲁棒规划

**Distributionally robust planning for data center park considering operational economy and reliability**

期刊：Energy；年份：2024；本地状态：在已检查文档中未命中完整英文题名。

[ScienceDirect原文页面](https://www.sciencedirect.com/science/article/pii/S036054422303579X) · [DOI](https://doi.org/10.1016/j.energy.2023.130185)

研究侧重点：协调数据中心、光伏、储能等资源，考虑故障状态任务调度与供需不确定性。

对本研究的用途：参考经济性与可靠性的容量规划权衡，以及不确定性下的约束设计。

适用边界：对象是园区并含柔性变电站，可提取储能和可靠性相关部分。

## 建议阅读顺序

已总结的第1、2、5、9、12篇可以直接复用笔记。新增论文建议从第3、4、6、7、8、10篇开始，分别对应负荷模型、AI任务SLA、灵活性贡献分解、任务转移代价、电池退化与可靠性、动态冷却功耗。

第15篇官网标注2027年卷期，现可检索；其秒级爬坡控制与本研究年度容量配置的时间尺度不同，主要参考GPU负荷建模。

建议优先检验的研究问题：在风光装机固定、满足同一组GPU任务SLA与绿电约束的条件下，引入任务时间灵活性后，储能功率、储能容量、购电费用、最大需量和电池寿命损耗分别如何改变；动态冷却功耗是否改变任务追随绿电的最优时段。

建议对照组：固定任务时序且无新增储能；固定任务时序且优化储能；任务调度且无新增储能；任务—储能联合优化。若某组不能满足绿电或供电约束，应报告不可行性，或另设放松约束的诊断结果。
