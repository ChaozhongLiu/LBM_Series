# 生命科学大模型系列 - 前沿探究

本项目旨在对生命科学领域内 DNA、RNA、单细胞、蛋白质、及多模态大模型的前沿进展作深入细致的学习和探讨，包括领域整理回顾、论文精读、代码讲解复现、应用延展、以及个人思考和观点。  
  
**项目主页**: 
- [知乎](https://www.zhihu.com/column/c_1766789616634736640)


## 论文精读计划

| 模型 | 发布日期 | 领域 | 状态 |
| --- | --- | --- | --- |
| [DNABERT](https://academic.oup.com/bioinformatics/article/37/15/2112/6128680) | 08/2021 | DNA | :white_check_mark: 已解读 |
| [RNABERT](https://academic.oup.com/nargab/article/4/1/lqac012/6534363) | 08/2021 | RNA | :white_check_mark: 已解读 |
| [scBERT](https://www.nature.com/articles/s42256-022-00534-z) | 09/2022 | scRNA | :white_check_mark: 已解读 |
| [GeneFormer](https://www.nature.com/articles/s41586-023-06139-9) | 04/2023 | scRNA | :white_check_mark: 已解读 |
| [scGPT](https://www.nature.com/articles/s41592-024-02201-0) | 05/2023 | scRNA | :white_check_mark: 已解读 |
| [DNABERT-2](https://arxiv.org/abs/2306.15006) | 06/2023 | DNA | :white_check_mark: 已解读 |
| [scFoundation](https://www.biorxiv.org/content/10.1101/2023.05.29.542705v4) | 06/2023 | scRNA | :white_check_mark: 已解读 |
| [HyenaDNA](https://arxiv.org/abs/2306.15794) | 06/2023 | DNA | :white_check_mark: 已解读 |
| [DNAGPT](https://arxiv.org/abs/2307.05628) | 07/2023 | DNA | :white_check_mark: 已解读 |
| [GeneCompass](https://www.nature.com/articles/s41422-024-01034-y) | 09/2023 | scRNA | :white_check_mark: 已解读 |
| [Orthrus](https://www.biorxiv.org/content/10.1101/2024.10.10.617658v1) | 10/2024 | RNA | :white_check_mark: 已解读 |
| [Evo](https://www.science.org/doi/10.1126/science.ado9336) | 11/2024 | DNA | :black_square_button: 准备中 |
| [xTrimoPGLM](https://arxiv.org/abs/2401.06199) | 01/2024 | Protein |
| [gLM](https://www.nature.com/articles/s41467-024-46947-9) | 05/2023 | DNA |
| [BigRNA](https://www.biorxiv.org/content/10.1101/2023.09.20.558508v1) | 09/2023 | RNA |
| [SaProt](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v2) | 10/2023 | Protein |
| [UTR-LM](https://www.nature.com/articles/s42256-024-00823-9) | 02/2024 | RNA |
| [GenePT](https://www.biorxiv.org/content/10.1101/2023.10.16.562533v2) | 03/2024 | scRNA |
| [NicheFormer](https://www.biorxiv.org/content/10.1101/2024.04.15.589472v1) | 04/2024 | sc+Spatial RNA |
| [OpenCRISPR](https://www.biorxiv.org/content/10.1101/2024.04.22.590591v1) | 04/2024 | Protein |
| [CRISPR-GPT](https://arxiv.org/abs/2404.18021) | 04/2024 | CRISPR |
| [RNAErnie](https://www.nature.com/articles/s42256-024-00836-4) | 05/2024 | RNA |
| [DrugLLM](https://arxiv.org/abs/2405.06690) | 05/2024 | Molecule |
| [LucaOne](https://www.biorxiv.org/content/10.1101/2024.05.10.592927v1) | 05/2024 | Multi-Omics |
| [RNAGenesis](https://www.biorxiv.org/content/10.1101/2024.12.30.630826v1) | 12/2024 | RNA |
| [RhoFold+](https://www.nature.com/articles/s41592-024-02487-0) | 11/2024 | RNA |
| [scLong](https://www.biorxiv.org/content/10.1101/2024.11.09.622759v2) | 11/2024 | scRNA |
| [stFormer](https://www.biorxiv.org/content/10.1101/2024.09.27.615337v5) | 11/2024 | Spatial |



还有一些没有计划解读的相关论文  
| 模型 | 发布日期 | 领域 |
| --- | --- | --- |
| [GeneSLMs](https://www.biorxiv.org/content/10.1101/2022.10.10.511571v2) | 11/2022 | DNA |
| [Nucleotide Transformer](https://www.biorxiv.org/content/10.1101/2023.01.11.523679v3) | 01/2023 | DNA |


## 文章目录
- (一) 导论&引言：大模型时代下的计算生物学 [知乎文章](https://zhuanlan.zhihu.com/p/694454155)
- (二) DNABERT 技术解读 [知乎文章](https://zhuanlan.zhihu.com/p/695657992)
- (三) RNABERT 技术简报 [知乎文章](https://zhuanlan.zhihu.com/p/696708056)
- (四) scBERT 技术解读 | scRNA-seq 的语言建模进行精准的细胞类型注释 [知乎文章](https://zhuanlan.zhihu.com/p/698575648)
- (五) Geneformer 技术解读 ｜ 利用基因名字排序进行语言建模 [知乎文章](https://zhuanlan.zhihu.com/p/700679229)
- (六) scGPT｜独特的 Tokenization 体系和生成式预训练策略下的单细胞基座模型 [知乎文章](https://zhuanlan.zhihu.com/p/702698466)
- (七) DNABERT-2 | BPE 和新技术加持下 DNABERT 的进化 [知乎文章](https://zhuanlan.zhihu.com/p/704373114) | [BPE 代码](notebooks/DNABERT2_Tokenizer.ipynb)
- (八) scFoundation | Read-Depth-Aware 的 scRNA-seq 预训练基座模型 [知乎文章](https://zhuanlan.zhihu.com/p/706311907)
- (九) HyenaDNA 技术解读 | 基于 Hyena 架构的超长 DNA 序列预训练模型 [知乎文章](https://zhuanlan.zhihu.com/p/708848430)
- (十) DNAGPT 技术解读 | 普适于多类下游任务的生成式预训练模型 [知乎文章](https://zhuanlan.zhihu.com/p/714612874)
- (十一) GeneCompass | 知识驱动的跨物种单细胞基座模型 [知乎文章](https://zhuanlan.zhihu.com/p/8553664471)
- (十二) Orthrus - 上 ｜预备知识：Mamba 架构 [知乎文章](https://zhuanlan.zhihu.com/p/12683528224)
- (十三) Orthrus - 下 | 基于 Mamba 架构与对比学习的 RNA 基座模型 [知乎文章](https://zhuanlan.zhihu.com/p/14970067631)

