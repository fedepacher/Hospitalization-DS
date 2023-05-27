# **Hospitalization-DS**

## **Approach to the problem**

We have been hired in the data science team at a renowned consultancy. We have been assigned to a health care study project for a major hospital. **Our client wants to know the most important characteristics of patients with a certain type of disease that end up in hospitalization.** A case was defined as a patient who underwent a prostate biopsy and who in a maximum period of 30 days after the procedure had fever, urinary tract infection, or sepsis; requiring outpatient or hospitalized medical management for the resolution of the complication and as a control the patient who underwent a prostate biopsy and who did not present infectious complications in the period of 30 days after the procedure. Since they have in their database some data referring to patients and results of diagnostic tests, of hospitalized and non-hospitalized patients, they have provided us with this information.

For this, our data department has compiled `Patient history`, `Patient-associated morbidity` and `Biopsy-related history` and `Infectious complications`. An associated data dictionary is found in the following table:

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)

The data department warns that there are some data quality problems in the information provided, so the first challenge for the team is to carry out an exploratory analysis of the data in order to adequately transform and prepare the data.

This project will consist of three phases:

- `Exploratory data analysis`
- `Data preparation`
- `Modeling and evaluation`

>Note: Our client wants to know the most important characteristics of patients with a certain type of disease that end up in hospitalization and create a predictive classification model for the objective variable: Hospitalization.