Adaptive Graph Fusion Network 
====================================

This repository serves as the official public project page for the paper:

Cifci MA, Öney B, Yildirim F, Yılmaz Başer H, Zontul M.  
"Interpretable Adaptive Graph Fusion Network for Mortality and Complication Prediction in ICUs."  
Diagnostics, 2025, 15(22):2825.  
DOI: [10.3390/diagnostics15222825](https://doi.org/10.3390/diagnostics15222825)

---

### Overview
The Adaptive Graph Fusion Network (AGFN) is an interpretable graph-based deep learning model for early ICU outcome prediction using complex, time-evolving patient data.  
AGFN integrates relational, temporal, and density-adaptive representations to predict six clinical endpoints:

- Mortality  
- Sepsis  
- Acute Kidney Injury (AKI)  
- Respiratory Failure  
- Cardiac Arrest  
- Prolonged ICU Stay  

AGFN dynamically adjusts neighborhood density using a Gaussian kernel (DA-KNN), combines CNN and GRU temporal encoders, and fuses representations with attention-based learning to achieve high interpretability and robust performance on imbalanced ICU data.

---

### Paper Access
The open-access version of the paper can be viewed or downloaded below once uploaded:  
- **PDF:** [`diagnostics-2025-agfn.pdf`](diagnostics-2025-agfn.pdf)

---

### Authors and Affiliations

**Dr. Mehmet Akif Çifci**  
Associate Professor and Research Scientist  

---

### Professional Profiles

- **LinkedIn:** [https://www.linkedin.com/in/themanoftalent](https://www.linkedin.com/in/themanoftalent)  

---

### Dataset
This study uses the **eICU Collaborative Research Database** (v2.0, PhysioNet), containing over 200,000 ICU admissions from 208 hospitals in the United States.  
Access requires credentialed approval via [PhysioNet](https://physionet.org/content/eicu-crd/2.0/).  
Raw patient-level data are not distributed here due to privacy regulations.

---

### Citation
If you use or refer to AGFN, please cite:

Cifci MA, Öney B, Yildirim F, Yılmaz Başer H, Zontul M.  
"Interpretable Adaptive Graph Fusion Network for Mortality and Complication Prediction in ICUs."  
Diagnostics, 2025, 15(22):2825. DOI: [10.3390/diagnostics15222825](https://doi.org/10.3390/diagnostics15222825)

---

### License
This project page is distributed under the Apache-2.0 License.
