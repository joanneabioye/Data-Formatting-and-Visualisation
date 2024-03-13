# Data Formatting and Visualisation

For my third project, my aim was to analyse data to determine whether there exists a correlation between patients' age, cholesterol levels, blood pressure, diabetes, and the diagnosis of heart disease.
I utilised two datasets for this analysis: the Heart Disease Data Set from the UCI Repository and the Heart Failure Clinical Records Dataset. The Heart Disease Data Set from the UCI Repository comprised four databases sourced from different clinical practices:
1.	Cleveland Clinic Foundation
2.	Hungarian Institute of Cardiology
3.	V.A. Medical Centre, Long Beach
4.	University Hospital, Zurich, Switzerland

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/e02f7024-e248-4d78-8930-237c6c55c54d)

Initially, I cleaned the data by eliminating blank rows, formatting cells, and enhancing visual clarity. Subsequently, I analysed the data from each clinic by generating pivot charts to illustrate the age distribution of patients included in the datasets. For instance, the data from the ‘processed va’ worksheet displayed a negatively skewed distribution, with the majority of patients falling between 54 and 66 years old, and an average age of 59 years. Cleveland also exhibited a negatively skewed distribution, average age of 54, while Hungary and Switzerland showed a positively skewed distribution. The average as for Hungry worksheet was 48 and 55 for the Switzerland.

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/dc97bd0a-78bb-4da0-a2c5-ab8fa43c7af6)

Following this, I computed the average cholesterol and blood pressure for patients with and without heart disease separately, and used a COUNTIFS formula to calculate patients with diabetes and heart disease and diabetic patients without heart disease, presenting the findings in a pivot chart. With the exception of Hungary, all clinics demonstrated higher blood pressure and cholesterol levels and diabetes among patients with heart disease.

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/42645323-6208-4069-ae55-f90b944d4332)

To further compare data across clinics, I combined all worksheets and conducted the same analysis. The results differed significantly, with the chart depicting patients' ages showing a positively skewed distribution and an average age of 52 years.

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/3dc776cb-65eb-46e2-a2aa-284233a449bd)

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/e982f817-e5e9-49b2-bfd8-07fa72ba4409)

Additionally, I investigated the relationship between heart disease and patients' sex, recording the results in a pivot table and chart. Using an IF formula in a new column, I categorised patients with and without heart disease, enhancing visual clarity. The visual representation indicated a notably higher prevalence of heart disease among males. 

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/00ee401a-559e-4711-b48c-d6ebfe5306ee)

Furthermore, I explored the correlation between patients' age and the presence of heart disease, revealing a negatively skewed distribution with the most common age of diagnosis ranging between 56 and 61 years, along with a notable outlier at age 38.

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/10d59bca-ceb2-4cf8-9faf-583e61aa36d8)

In summary, my analysis reveals a higher prevalence of heart disease among males compared to females, with the average age of patients being 54 years. Initial findings suggest a correlation between high cholesterol, high blood pressure and diabetes in the diagnosis of heart disease.
Incorporating data on patients' blood sugar levels, could enhance visualization and comparison against cholesterol and blood pressure values, rather than Boolean values. 

Subsequently, I examined the Heart Failure Clinical Records dataset, noting variations in terminology compared to the previous dataset. I adjusted the terminology accordingly to corelate with one and other. For instance, while the UCI workbook referred to diabetics as 'FBS' for fasting blood sugars, the clinical records workbook labelled this as 'diabetes', with both datasets categorising results as either 0 (non-diabetic) or 1 (diabetic).
Carrying out similar investigations as the previous dataset on heart disease in association with diabetes, blood pressure and cholesterol, age and gender. 
Furthermore, my findings indicate that patients without heart disease tend to exhibit higher blood pressure and diabetes levels. However, since the datasets lack information on medication usage for these conditions, the results may not be entirely conclusive.

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/7090c995-3ba1-4372-89d9-91c21b6ffdd3)

The average age of heart disease diagnosis in this dataset is 60 years, with spikes occurring at birthday milestones, possibly due to routine check-ups by GP practices. 

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/488b7962-164e-4deb-9d94-c59adc6e968f)

Gender-wise, although there are more males than females in the dataset, the percentages of heart disease diagnoses are equal for both genders.

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/e5edc196-ddc7-4b3b-a9fa-d97ad9fce905)

Out of 299 patients, 96 had heart disease (32%) and 203 patients did not have heart disease (68%)
194 were male (65%) and 105 were female (35%)					
Out of 194 males, 62 had heart disease (32%) and 132 did not have heart disease (68%)
Out of 105 females, 34 had heart disease (32%) and 71 did not have heart disease (68%)

![image](https://github.com/joanneabioye/Data-Formatting-and-Visualisation/assets/153685683/c9159fce-f542-48fb-aa6a-93979492af9d)
		
While these insights shed light on general associations, a more comprehensive analysis incorporating factors like medication usage, ethnicity, diet, genetics, BMI, fitness level, and diabetes type, alongside balanced gender representation, is necessary for robust conclusions.
Additionally, further investigations could explore hypotheses such as the impact of age and smoking on heart disease diagnosis, as well as the potential correlation between reduced serum creatinine and decreased ejection fraction leading to increased heart disease diagnoses.

