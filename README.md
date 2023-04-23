# Prediction-of-hospital-readmission

__Problem Statement__:
Impact of Medication for Lifestyle Diseases on Hospital Readmission –
Management  of lifestyle diseases in hospitalized patients has a significant bearing on outcome, in terms of both morbidity and mortality.

__Objective__:
The main objective for this problem is to predict whether a patient is likely to be readmitted to hospital based on the previous details of the patient.

__Solution__
‘readmitted’  is the target variable  with two labels ‘0’ and ‘1’ which denotes ‘not readmitted’ and ‘readmitted’ respectively.

* Exploratory Data Analysis - 
* 1) For continuous columns I have performed missing value check and found that ‘race’, ‘weight’,’medical_specialty’, ‘diag_1’,’diag_2’ , ‘diag_3’ , ‘diag_4’
  2) Univariate Analysis - From histogram plots, it is quite evident that encounter_id', 'patient_id', 'num_lab_procedures', 'num_medications', 'number_outpatient', 'number_emergency’ are highly skewed continuous columns hence they need skewness treatment.

  !













