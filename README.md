# Stroke EDA

> A stroke, sometimes called a brain attack, occurs when something blocks blood supply to part of the brain or when a blood vessel in the brain bursts.
In either case, parts of the brain become damaged or die. A stroke can cause lasting brain damage, long-term disability, or even death.
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
Do you know, 80% Heart strokes are preventable?, yes they are. Here I visulize some key indicators that lead to heart strokes.
Here data is sampled from a wide range of age groups, gender, habits and health related issues.

This dataset was gotten from Kaggle https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset.
 The stroke dataset consists of 5110  records of patients data.
This dataset is made up of 12 columns of patients records.

These columns are:

id: Identification number of the individual.

gender: Gender of the individual, which is either Male or Female.

hypertension: Health related parameter, also known a high blood pressure. Does person have hypertension.

heart_disease: Health related parameter, does person have heart disease.

ever_married: Personal information, is person married on not?

work_type: Nature of work place.

Residence_type: Residence type of the individual.

avg_glucose_level: average glucose level in blood for the individual.

bmi: body mass index of the individual.

smoking_status: Habitual information. Current smoking status of individual.

stroke: Our taget, is person suffered stroke?

 ## Data wrangling
 > The data was not a really dirty data , so just few things were done here.
 
 1. I converted the age column to int.
 2. I converted the id column to object.
 3. I replaced the null values in the BMI column with the mean.
 
 ## Data Exloration
 > Here I carried out univariate, bivariate and multivariate analysis.
 
 ## Key Insights
1. From the distribution gender is not a high determinant of stroke, both male and female gender have equal chances of getting stroke.
2. Married people have a higher risk of getting stroke.
3. Patients that are 60 years and above have a higer risk of getting stroke.
4. A high distribution of the patients have a normal glucose level of 90mg/dL.
5. Patients with bmi of 25kg/m2 and above have a higher risk of getting stroke
6. Percentage of patients with hypertension & stroke and patients with heart disease & stroke is higher in the distribution, but patients with hypertension and no heart disease have a higher risk of getting stroke from the dataset.
 
