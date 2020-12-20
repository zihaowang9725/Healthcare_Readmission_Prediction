# Healthcare_Readmission_Prediction

## Abstract
As a general goal for the US healthcare system, reducing per capita cost without compromising patient or population health and quality of care is of the utmost importance. The issue of readmission opens up an avenue for potential cost reduction and highlights the need for collaboration between the government and hospitals. In the past, these two organizations have worked against each other towards a common goal, but not in coordination. The solution is twofold: firstly, data driven models must be at the forefront of decision making, and secondly, hospitals as a business must buy into the idea that it is best to move from fee-for-service to value-based care in order to achieve the goal of optimal communal health. It is empirical to look into the drivers of readmission and act proactively, rather than after the readmission has occurred. In this project, we utilized machine learning methods such as Naive Bayes, Decision Tree, Confusion Matrix, KNN and Random Forest to help predict which patients are likely to readmit. This information will be used to reduce cost while prioritizing value-based patient care.

## Business Implications
Readmissions to the hospital are detrimental to patients and the overall reputation of the hospital from a governmental stanpoint. About 20% of Medicare patients are readmitted to the hospitals (Jenks ). The Center for Medicare Management (CMS) has created a penalty for readmission which has made the point clear—the US Government is demanding structural change in large hospital organizations focusing heavily on value-based care.
The transition from fee-for-service to a value-based environment in providing care for patients is costly across the continuum. In doing this, the hospital must address gaps which are not directly reimbursable. The return on investment is ultimately through readmission penalty avoidance and decrease in cost per Medicare beneficiary. Hospitals are also incentivised by governmental assistance/reimbursement for transitional and chronic care. 
Lowering the number of patient readmissions will yield lower penalty cost overall, ultimately saving the hospital money. However, at the root of this understanding are the reasons why patients are readmitted to begin with. As expected, this is a complex and multidimensional issue regarding the overall quality of patient care, where important details often fall through the cracks. Of key importance are factors such as: post discharge care issues, not having a primary care physician, misunderstanding of their treatment regimen/aftercare, and a lack of health literacy in general.
The solution is twofold: firstly, data driven models must be at the forefront of decision making, and secondly, hospitals as a business must buy into the idea that it is best to move from fee-for-service to value-based care in order to achieve the goal of optimal communal health. It is empirical to look into the drivers of readmission and act proactively, rather than after the readmission has occurred. 

## Data Summary

### Dataset Source: 
The dataset is obtained from a Governmental website, specifically: Agency for Healthcare Research and Quality

### Dataset Description:
The original dataset contains patients' visit records in 49.7% hospitals in the States from 2010 to 2017
5 random hospitals were chosen from the United States with over 25,000 cases
24 variables out of 101 original variables are chosen initially

## Modeling and Data Visulization (See Code)

## Conclusion

Lowering the number of patient readmissions will not only yield lower penalty costs, saving the hospital billions of dollars, it also improves the overall health of the community. High readmission rates ultimately reflect poor quality of care and reducing this is ideal. This win-win situation for patients and community alike is at the forefront of our research. For our analysis, we intended to tackle the root cause for the reasons why patients readmit so that we can provide data-driven solutions to both the hospital and Government in their mutual best interest. After properly accounting for unbalanced and unclean data, robust machine learning models allude to several important findings. 

Of the more interesting findings, we found that the dollar amount charged was found to be the most significant feature in predicting readmission rather than age. We think this is likely due to the fact that more advanced treatments are usually linked to more severe diseases which require greater aftercare and more attention overall. Age was also found to be significant due to the increased immunocompromised nature of elderly patients, where comorbidity and mortality risk is high.

Surprisingly, the third feature contributing most to impurity reduction of classification is the month the patient was discharged, placing higher than the length of stay and the count of unique chronic diagnoses reported on the discharge date. In March, April, May, June, July, November, and December, there were more readmission visits than non-readmission visits. This indicates the rate of readmission is highly based on seasonality. We think this might be because there are more flu cases in the Spring and Winter. Some further investigations can be done in order to help the hospitals prepare better to reduce the readmission situation.

The recommendations to the hospitals can be expanded to other areas in the United States because patient profiles will be similar. With our ultimate goal of reducing avoidable cost, these models should be utilized to assess risk of readmission. 

