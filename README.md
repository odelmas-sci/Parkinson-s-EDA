# Parkinson-s-EDA
EDA of parkinson's risk factors
kaggle dataset:https://www.kaggle.com/datasets/rabieelkharoua/parkinsons-disease-dataset-analysis?resource=download

PatientID: A unique identifier assigned to each patient (3058 to 5162).

Demographic Details:
Age: The age of the patients ranges from 50 to 90 years.
Gender: Gender of the patients, where 0 represents Male and 1 represents Female.
Ethnicity: The ethnicity of the patients, coded as follows:
   0: Caucasian
   1: African American
   2: Asian
   3: Other
EducationLevel: The education level of the patients, coded as follows:
   0: None
   1: High School
   2: Bachelor's
   3: Higher

Lifestyle Factors:
BMI: Body Mass Index of the patients, ranging from 15 to 40.
Smoking: Smoking status, where 0 indicates No and 1 indicates Yes.
AlcoholConsumption: Weekly alcohol consumption in units, ranging from 0 to 20.
PhysicalActivity: Weekly physical activity in hours, ranging from 0 to 10.
DietQuality: Diet quality score, ranging from 0 to 10.
SleepQuality: Sleep quality score, ranging from 4 to 10.

Medical History (0 = No, 1 = Yes):
FamilyHistoryParkinsons: Family history of Parkinson's Disease, where 0 indicates No and 1 indicates Yes.
TraumaticBrainInjury: History of traumatic brain injury, where 0 indicates No and 1 indicates Yes.
Hypertension: Presence of hypertension, where 0 indicates No and 1 indicates Yes.
Diabetes: Presence of diabetes, where 0 indicates No and 1 indicates Yes.
Depression: Presence of depression, where 0 indicates No and 1 indicates Yes.
Stroke: History of stroke, where 0 indicates No and 1 indicates Yes.

Clinical Measurements:
SystolicBP: Systolic blood pressure, ranging from 90 to 180 mmHg.
DiastolicBP: Diastolic blood pressure, ranging from 60 to 120 mmHg.
CholesterolTotal: Total cholesterol levels, ranging from 150 to 300 mg/dL.
CholesterolLDL: Low-density lipoprotein cholesterol levels, ranging from 50 to 200 mg/dL.
CholesterolHDL: High-density lipoprotein cholesterol levels, ranging from 20 to 100 mg/dL.
CholesterolTriglycerides: Triglycerides levels, ranging from 50 to 400 mg/dL.

Cognitive and Functional Assessments:
UPDRS: Unified Parkinson's Disease Rating Scale score, ranging from 0 to 199. Higher scores indicate greater severity of the disease.
MoCA: Montreal Cognitive Assessment score, ranging from 0 to 30. Lower scores indicate cognitive impairment.
FunctionalAssessment: Functional assessment score, ranging from 0 to 10. Lower scores indicate greater impairment.

Symptoms (0 = No, 1= Yes):
Tremor: Presence of tremor, where 0 indicates No and 1 indicates Yes.
Rigidity: Presence of muscle rigidity, where 0 indicates No and 1 indicates Yes.
Bradykinesia: Presence of bradykinesia (slowness of movement), where 0 indicates No and 1 indicates Yes.
PosturalInstability: Presence of postural instability, where 0 indicates No and 1 indicates Yes.
SpeechProblems: Presence of speech problems, where 0 indicates No and 1 indicates Yes.
SleepDisorders: Presence of sleep disorders, where 0 indicates No and 1 indicates Yes.
Constipation: Presence of constipation, where 0 indicates No and 1 indicates Yes.

Diagnosis Information:
Diagnosis: Diagnosis status for Parkinson's Disease, where 0 indicates No and 1 indicates Yes.

Confidential Information:
DoctorInCharge: This column contains confidential information about the doctor in charge, with "DrXXXConfid" as the value for all patients.
