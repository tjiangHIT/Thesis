# 博士论文

## 基于第三代测序数据的基因组结构变异检测方法研究

摘  要
-
随着测序技术的不断成熟和广泛应用，以测序技术为驱动的基因组、转录组等多组学的研究得到了跨越式发展，推动了基因组科学、遗传学、临床医学等多学科的变革。基因组变异检测作为基因组研究中最为核心和关键的环节，对于基因组注释、与疾病和表型的关联分析、临床诊断等具有重要的意义。然而，由于基因组存在大量复杂的结构变异，现有的检测技术和方法在变异检测的准确性、敏感性、全面性以及性能上已无法满足当前基因组前沿研究的需求，在日益增长的海量测序数据面前面临着巨大的挑战。
本文全面总结了基因组结构变异识别和检测的基本方法与途径，重点分析了现阶段结构变异检测面临的难点与问题。本文以提升结构变异检测精度和计算性能等方面作为切入点，针对性的开展一系列相关的研究与实践，开发了多款基因组结构变异检测方法以及工具，有效地解决当前基因组研究中多个瓶颈问题。本文的主要研究内容如下：

（1）针对大规模高相似性的移动元件变异难以准确、敏感检测这一问题，本文研究了一种基于片段重比对的基因组移动元件变异检测方法rMETL。该方法采用创新性的序列重比对方法，将测序片段的异常比对序列部分与已知移动元件进行重新比对，使复杂多样的局部比对信息转换为具有高度一致性的移动元件变异证据信息。在国际权威测序数据集上的实验结果表明，rMETL能有效提升移动元件变异检测的敏感性，并保持较高的检测准确性。这一方法有助于移动元件变异的精准发现，挖掘更多与疾病和表型的关联，是一款重要的前沿科研工具。

（2）针对现有结构变异检测工具无法检测参考基因组之外的DNA序列这一问题，本文研究了一种基于局部序列拼接与聚类的基因组新序列插入变异检测方法rCANID。该方法以新序列插入变异形态为出发点，结合局部拼接手段，通过对异常比对片段和未比对片段的双重聚类和拼接，分别重构靠近插入边界和远离插入边界的两类新序列插入变异局部序列，并通过启发式算法连接和合并两类局部序列从而检测完整的新序列插入变异。在国际权威测序数据集上的实验结果表明，rCNAID算法较之现有结构变异检测算法，能有效提升新序列插入变异的检测敏感性，有利于发现样本所特有的DNA序列，对一些罕见疾病的发现和治疗具有重要的生物学意义。

（3）针对当前结构变异检测技术的识别率和敏感性仍然处于较低水平的现状，本文研究了一种基于多特征融合的基因组结构变异检测方法cuteSV。该方法采用创新性的多重特征融合聚类方法，将异常测序片段中的多重变异信号聚类，利用多种基因组空间结构信息对结构变异进行进一步整合，在显著提升变异检测的识别率和敏感性的同时，兼顾发现复杂变异的能力。在国际权威测序数据集上的实验结果表明，cuteSV是目前领域内结构变异检测综合性能最好，计算性能最优的一款工具。该工具将为相关的基因组工程分析带来全新的支持。

（4）针对现阶段结构变异检测的计算瓶颈问题，本文研究了一种基于测序片段过滤的基因组结构变异检测工作流加速方法rMFilter。该方法首创区域哈希表索引和区域种子命中快速统计方法，通过对测序片段的准确、快速分类，在数据分析源头极大地减少输入数据量，从根本上降低结构变异检测工作流的计算代价。在国际权威测序数据集上的实验结果表明，rMFilter与主流结构变异检测工作流组合使用，使基于第三代测序数据的结构变异检测速度整体提升一倍以上，并取得了与原始工作流相同的变异检测结果。该工具可以有效提升结构变异检测分析速度，为大规模基因组分析任务带来曙光。

本文以基因组结构变异检测为重点，以全面提升基因组结构变异检测的准确性、敏感性、多样性和计算性能为目的，充分发挥第三代测序数据的优势。通过开发多种类型结构变异检测方法和工具，切实解决现阶段基因组研究中的瓶颈问题，全面有效地推动以基因组结构变异为导向的相关研究的发展，为基因组前沿科学研究提供了新的研究思路、技术手段与理论支撑，具有很高的实际意义。

关键词
-
第三代测序技术；结构变异检测；局部序列拼接；序列重比对；变异检测加速
