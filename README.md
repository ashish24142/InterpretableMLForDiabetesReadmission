# InterpretableMLForDiabetesReadmission

## NOTE:
In GitHub the notebook might not get rendered properly, so please use the below link to look at the results:

https://nbviewer.jupyter.org/github/ashish24142/InterpretableMLForDiabetesReadmission/blob/master/Interpretable%20ML%20for%20Risk%20of%20Readmission.ipynb

But you can clone the repo and look at the solution, as well.

## Basic Explanation

It is important to know if a patient will be readmitted in some hospital. The reason is that you can change the treatment, in order to avoid a readmission.

In this database, you have 3 different outputs:

1. No readmission;
2. A readmission in less than 30 days 
3. A readmission in more than 30 days 

## About the Data

"The data set represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.

It is an inpatient encounter (a hospital admission).
It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
The length of stay was at least 1 day and at most 14 days.
Laboratory tests were performed during the encounter.
Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc."
## Source

The data are submitted on behalf of the Center for Clinical and Translational Research, Virginia Commonwealth University, a recipient of NIH CTSA grant UL1 TR00058 and a recipient of the CERNER data. John Clore (jclore '@' vcu.edu), Krzysztof J. Cios (kcios '@' vcu.edu), Jon DeShazo (jpdeshazo '@' vcu.edu), and Beata Strack (strackb '@' vcu.edu). This data is a de-identified abstract of the Health Facts database (Cerner Corporation, Kansas City, MO). Original source of the data set

https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008

## Motivation
## Motivation behind this solution is following:

1. To create a model to predict readmission, so that the patient can get a better treatment.
2. Diabetes is a world-wide problem, and we should try to understand the cause & factors of Diabetes.
3. This is a try to implement modelling as well as explanation of the models.

Note: This might not be a perfect solution, as this has been created with limited time and effort, so please don't use it for medical purposes, but yes this can be used for educational purposes.
