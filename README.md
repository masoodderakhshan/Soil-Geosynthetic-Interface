# Machine Learning Modelling and Interpretation of Soil–Geosynthetic Interface Shear Behaviour: A Comparison of Gradient Boosting and Neural Network Algorithms

### 📝 Status

**Journal:** Structure and Infrastructure Engineering (Submitted)
**License:** [![Status](https://img.shields.io/badge/Status-Submitted-blue)](https://www.Elsevier.com/journal/11069)
[![Journal](https://img.shields.io/badge/Journal-StructureandInfrastructureEngineering-orange)](https://www.Elsevier.com/journal/11069)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📌 Abstract

Characterizing the complex shear behaviour of soil-geosynthetic interfaces is a fundamental aspect of geotechnical design, yet it is often constrained by the prohibitive costs and time requirements of large-scale laboratory testing. This study proposes a robust data-driven framework employing Machine Learning (ML) to predict the complete stress-strain response and critical shear strength parameters (cohesion, friction angle, and interaction coefficients) for interfaces between marginal soils and geosynthetics. We evaluated four advanced regression algorithms—Multilayer Perceptron (MLP), Light Gradient Boosting Machine (LightGBM), XGBoost, and CatBoost—using a comprehensive dataset derived from 108 large-scale direct shear tests. The dataset encompassed two marginal soil types and five distinct geosynthetic reinforcements under varying normal stresses and moisture contents. Performance analysis revealed that ensemble learning models significantly outperformed the neural network approach. The CatBoost model demonstrated superior predictive accuracy, achieving a coefficient of determination (R2) of 0.9988, a root mean squared error (RMSE) of 0.9488 kPa, and a mean absolute error (MAE) of 0.6145 kPa. Feature importance analysis via SHAP and Mutual Information identified normal stress as the dominant predictor of shear behavior. Furthermore, the models elucidated distinct interaction mechanisms: increased moisture content degraded interface strength in the coarser soil (S1) but enhanced it in the finer, cohesive soil (S2) due to matric suction. Notably, the geotextile-sand composite (GTSand) interface consistently yielded the highest interaction coefficients, establishing it as the most effective reinforcement across all tested conditions.

Keywords: Geosynthetics; marginal soil; soil-geosynthetic interface; Machine Learning; CatBoost; shear strength.



This repository includes the source codes and methodology for the article:

**"Machine Learning Modelling and Interpretation of Soil–Geosynthetic Interface Shear Behaviour: A Comparison of Gradient Boosting and Neural Network Algorithms"**,
submitted to *Structure and Infrastructure Engineering*.


## 👥 Authors
* **Hamid Reza Razeghi**
    * *School of Civil Engineering, Iran University of Science and Technology (IUST), Tehran, Iran*
    * [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--7254--2958-green)](https://orcid.org/0009-0009-3453-8304)
* **Jaber Mamaghanian**
    * *School of Civil Engineering, Iran University of Science and Technology (IUST), Tehran, Iran*
    * [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--1340--2829-green)](https://orcid.org/0009-0009-3453-8304)
* **Masoud Ebrahimi Derakhshan**
    * *School of Civil Engineering, Iran University of Science and Technology (IUST), Tehran, Iran*
    * [![ORCID](https://img.shields.io/badge/ORCID-0009--0009--3453--8304-green)](https://orcid.org/0009-0009-3453-8304)
* **Mehrab Ramzani**
    * *School of Civil Engineering, Iran University of Science and Technology (IUST), Tehran, Iran*
    * [![ORCID](https://img.shields.io/badge/ORCID-0009--0003--7281--3051-green)](https://orcid.org/0009-0009-3453-8304)
* **Abbas Ensani**
    * *School of Civil Engineering, Iran University of Science and Technology (IUST), Tehran, Iran*
    * [![ORCID](https://img.shields.io/badge/ORCID-0009--0001--6984--3028-green)](https://orcid.org/0009-0009-3453-8304)
---

## 📜 Citation

If you use this repository, please cite the following manuscript:

```
@article{Ebrahimi Derakhshan 2025 Subsidence,
  title={Machine Learning Modelling and Interpretation of Soil–Geosynthetic Interface Shear Behaviour: A Comparison of Gradient Boosting and Neural Network Algorithms},
  author={Razeghi, Hamid Reza ;Mamaghanian, Jaber ;Ebrahimi Derakhshan, Masoud;  Ramzani, Mehrab and Ensani, Abbas},
  journal={Structure and Infrastructure Engineering},
  year={2025},
  note={Submitted}
}
```
