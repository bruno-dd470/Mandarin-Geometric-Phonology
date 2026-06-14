# Tian-Dao-Phonology

[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.xxxxx-blue.svg)](https://doi.org/10.5281/zenodo.xxxxx)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)

## Mandarin Chinese Phonology as a 64→20 Topological Invariant: Empirical Validation of a Discrete Wuxing × Bagua Grid

### Abstract

The seminal work of Rowlands and Hill (2007) bridged particle physics and molecular biology, suggesting that a single algebraic-geometric structure underlies both fields. Building on this framework, we have recently formalized the substrate-independent topological reduction invariant 64→20. This article verifies that Mandarin phonology also obeys this structure: the analysis reveals the spontaneous emergence of a 5×8 combinatorial grid (Wuxing × Bagua) with 26 active cells out of 40 (65%) and 14 phonotactic gaps. The distribution of polarities follows the gradient of the invariant (Spearman ρ = 1.0000).

### Key Results

| Metric | Value |
|--------|-------|
| Active cells / 40 | **26 (65%)** |
| Phonotactic gaps | **14** |
| Spearman correlation | **ρ = 1.0000** |
| Chi-square | **χ² = 262.43 (p = 1.34e-56)** |
| 3N observed vs theoretical | **1.7% vs 5.0%** |

### Repository Structure

```
Tian-Dao-Phonology/
├── paper/                    # Final article
│   ├── v4_final_en.md
│   ├── v4_final_en.pdf
│   └── references.bib
├── scripts/                  # Analysis pipeline
│   └── analysis/
│       └── pipeline_chinese_phonology.py
        └── pipeline_phonologie_chinoise.py

├── data/                     # Phonetic dictionary
│   └── raw/
│       └── dictionnaire_phonetique.json
├── docs/                     # Documentation
│   └── theory/
│       └── template_FR.tex
└── results/                  # Generated figures
    └── figures_academiques/
```

### Reproduction

```bash
# Clone the repository
git clone https://github.com/username/Tian-Dao-Phonology.git
cd Tian-Dao-Phonology

# Install dependencies
pip install -r requirements.txt

# Run the pipeline
python scripts/analysis/pipeline_chinese_phonology.py
```

### Dependencies

- numpy ≥ 1.24.0
- pandas ≥ 2.0.0
- scikit-learn ≥ 1.3.0
- scipy ≥ 1.10.0
- matplotlib ≥ 3.7.0
- seaborn ≥ 0.12.0

### Citation

```bibtex
@article{DeDominicis2026,
  author    = {De Dominicis, Bruno},
  title     = {Mandarin Chinese Phonology as a 64→20 Topological Invariant},
  journal   = {Forthcoming},
  year      = {2026},
  doi       = {10.5281/zenodo.xxxxx}
}
```

### License

MIT License

### Contact

Bruno DE DOMINICIS - [ORCID: 0009-0009-0380-3056](https://orcid.org/0009-0009-0380-3056)


---

## 🇨🇳 中文版本


# 天道音韵学 (Tian-Dao-Phonology)

[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.xxxxx-blue.svg)](https://doi.org/10.5281/zenodo.xxxxx)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)

## 普通话语音学作为64→20拓扑不变量：五行×八卦离散网格的经验验证

### 摘要

Rowlands与Hill（2007）的开创性工作搭建了粒子物理学与分子生物学之间的桥梁，表明同一代数几何结构支撑着这两个领域。在此框架基础上，我们近期形式化了与基底无关的拓扑约化不变量64→20。本文验证了普通话语音学同样遵循这一结构：分析揭示了5×8组合网格（五行×八卦）的自发涌现，其中40个单元格中有26个活跃单元格（65%），以及14个音位配列空缺。极性分布遵循不变量的梯度（Spearman ρ = 1.0000）。

### 主要结果

| 指标 | 数值 |
|------|------|
| 活跃单元格 / 40 | **26 (65%)** |
| 音位配列空缺 | **14** |
| Spearman相关系数 | **ρ = 1.0000** |
| 卡方检验 | **χ² = 262.43 (p = 1.34e-56)** |
| 3N观察值 vs 理论值 | **1.7% vs 5.0%** |

### 仓库结构

```
Tian-Dao-Phonology/
├── paper/                    # 最终论文
│   ├── v4_final_en.md
│   ├── v4_final_en.pdf
│   └── references.bib
├── scripts/                  # 分析管道
│   └── analysis/
│       └── pipeline_chinese_phonology.py
├── data/                     # 语音字典
│   └── raw/
│       └── dictionnaire_phonetique.json
├── docs/                     # 文档
│   └── theory/
│       └── template_FR.tex
└── results/                  # 生成的图表
    └── figures_academiques/
```

### 复现结果

```bash
# 克隆仓库
git clone https://github.com/username/Tian-Dao-Phonology.git
cd Tian-Dao-Phonology

# 安装依赖
pip install -r requirements.txt

# 运行管道
python scripts/analysis/pipeline_chinese_phonology.py
```

### 依赖项

- numpy ≥ 1.24.0
- pandas ≥ 2.0.0
- scikit-learn ≥ 1.3.0
- scipy ≥ 1.10.0
- matplotlib ≥ 3.7.0
- seaborn ≥ 0.12.0

### 引用

```bibtex
@article{DeDominicis2026,
  author    = {De Dominicis, Bruno},
  title     = {Mandarin Chinese Phonology as a 64→20 Topological Invariant},
  journal   = {Forthcoming},
  year      = {2026},
  doi       = {10.5281/zenodo.xxxxx}
}
```

### 许可证

MIT 许可证

### 联系方式

Bruno DE DOMINICIS - [ORCID: 0009-0009-0380-3056](https://orcid.org/0009-0009-0380-3056)
