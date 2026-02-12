### 🌟 简介
------
本项目是对论文 [DOI: 10.3847/1538-4357/abb5b6](https://www.doi.org/10.3847/1538-4357/abb5b6) 的 **PyTorch** 实现。

核心逻辑参考自：[Zenodo](https://zenodo.org/records/3979217)。


### 📊 数据来源
------
本项目使用的数据来源于 **NASA Ames PAH IR Spectroscopic Database** ([PAHdb](https://www.astrochem.org/pahdb/))。
- **使用版本**：Library of Computed Spectra **3.20**。


### 🛠️ 推荐环境配置
------
建议在以下环境下运行以获得最佳兼容性：

- **Python**: `3.10.*`
- **PyTorch**: `2.5.1`


### 🏗️ 项目特点
------
相比于原始的版本，本项目在 PyTorch 框架下进行了重构：

- 更加灵活的数据加载流程（使用 `Dataset` 和 `DataLoader`）。
- 结构清晰的模型定义，便于后续进行模型微调。


### 📜 开源协议
---
本项目遵循 **[CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)**。
