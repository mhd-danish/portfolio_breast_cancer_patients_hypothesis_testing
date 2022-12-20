# Breast Cancer Patients - EDA and A/B Testing

**Dataset:** [Kaggle](https://www.kaggle.com/datasets/amandam1/breastcancerdataset)

## Objectives
Explore the dataset and extract insights from the data. Using statistical evidence to prove that

* Tumour stages are dependent of HER2-Status.
* There is a relationship between histology and HER2-Status.
* The effect of Proteins on patients' surival by tumour stages.
* Surgery performed on patient is dependent on his/her tumour stage
* The gender distribution is highly skewed
* Patients' survival curve differs by tumour stages

## Conclusions

1. Tumour Stage-II's HER2 postive status has smaller proportion than Tumour Stage-III's HER2 postive status.

    **P-value:** 0.01

    ![alt text](https://github.com/mhd-danish/portfolio_breast_cancer_patients_hypothesis_testing/blob/main/extras/tumour_her2.png)


2. Surgery Procedures greatly depend on the Patients' Tumour Stages.

    **P-value:** 0.000022

    ![alt text](https://github.com/mhd-danish/portfolio_breast_cancer_patients_hypothesis_testing/blob/main/extras/patients_sugery.png)

3. Tumour Stages are dependent on different Age groups.
    
    **P-value:** 0.01

    ![alt text](https://github.com/mhd-danish/portfolio_breast_cancer_patients_hypothesis_testing/blob/main/extras/tumour_age.png)

4. Although, we can't draw a definite conclusion that the male-patients/female-patients ratio is small due to smaller sample size (of male patients) but intuitively, the sheer difference speaks in it's favour.

    **P-value:** Nil | Since A/B Test is not applicable due to smaller sample size.

    ![alt text](https://github.com/mhd-danish/portfolio_breast_cancer_patients_hypothesis_testing/blob/main/extras/gender_age.png)