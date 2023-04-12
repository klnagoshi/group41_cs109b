# CS109b Final Project: Heart Disease Classification

MILESTONE 3 GOOGLE DOCUMENT: [https://docs.google.com/document/d/1uOqDRfzlNTzk3SJMBpSdcbuoPB_YwPJTBx2ISj3UBYw/edit?usp=sharing](https://docs.google.com/document/d/1uOqDRfzlNTzk3SJMBpSdcbuoPB_YwPJTBx2ISj3UBYw/edit?usp=sharing)

Update Log:
4/12/23 - Jordan

- Uploaded additional EDA file (EDA_JC.ipynb) with additional visualizations, will be merged with EDA.ipynb in the future

4/11/23 - Sonia

- Created csv files that group ECG signals by lead type across all 200 subjects, normalized using min-max scaling (files can be found in lead_csvs folder)
- Performed PCA visualization of ECG signals by lead type

4/11/23 - Kira

- Converted all Lobachevsky University files to readable csv files.

annotation_csvs = one file for each individual -- records the manual annotations for each lead (row numbers indicate the timepoint/particular sample that the annotation corresponds to.)

data_csvs = one file for each individual -- records the signal data. Each column is a lead, each row is one of the 5000 timepoints (each point is 1/500 of a second, recorded over 10 seconds).

characteristics = diagnoses, demographics, etc. for each of the 200 individuals in the study sample.
