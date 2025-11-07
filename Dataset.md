### Dataset

The **eICU Collaborative Research Database** (PhysioNet) provides de-identified data from more than 200,000 ICU stays across 208 hospitals in the United States. It includes two main groups of features:

- **Static variables:** age, sex, and comorbidities (around 10 features per patient)
- **Temporal variables:** lactate, creatinine, and vital signs recorded hourly over the first 24 hours of ICU stay

Temporal data are resampled to hourly resolution and imputed using forward fill. Static variables are imputed with median values when needed.  

Labels for the six binary outcomes are defined as follows:

- **Mortality:** derived from apachePatientResult  
- **Sepsis** and **acute kidney injury (AKI):** derived from diagnosis codes and clinical documentation  
- **Respiratory failure**, **cardiac arrest**, and **prolonged ICU stay:** derived from clinical criteria and ICU length of stay  

Access to eICU requires credentialed approval through [PhysioNet](https://physionet.org/content/eicu-crd/2.0/).  
Raw patient-level data cannot be redistributed here due to privacy regulations.  
The full preprocessing and label extraction pipeline that operates on eICU tables (for example, `patient.csv`, `lab.csv`, `vitalperiodic.csv`) is maintained in a private code repository and can be shared on reasonable request for non-commercial research use.
