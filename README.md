# Progress Report 2

## Title 1
 Find an appropriate modeling for UKBioBank.(, which is a highly promising dataset for brain biomarker research into population mental health due to its unprecedented sample size and extensive phenotypic, imaging, and biological measurements. )

### Narrative
As a researcher who want to use UKBioBank database frequently in the future,
I want to apply some different modeling approaches for UKBioBank,
so that I can find a most suitable machine learning model for UKBioBank and apply the model to predict many values like behavior, performance, mental state, disease risk, treatment response, and physiology.

### Acceptance criteria
Scenario 1: Adjust parameters to optimize the model, or abandon this implementation.
Given that I have already choose some appropriate features from the processed dataset based on UKBioBank
and implement a random forest modeling based on features,
when the accuracy of predictions produced by this machine learning modeling is very low,
then researcheres should not consider to use this random forest modeling to predict mental states of subjects.

Scenario 2: Applied this modeling for many different researches based on UKBioBank database.
Given that I have already choose some appropriate features from the processed dataset based on UKBioBank
and implement a deep learning modeling based on these features,
when the accuracy of predictions produced by the modeling is very high
and the modeling is not overfitting and not underfitting,
then researcheres can pick this deep learning model to do following researches on UKBioBank.

## Title 2
 Visualize features of datasets
who want to discover more relationships between head motions and mental states
### Narrative
(1.	Observe feature characteristic, 2check is there any problems within the datasets)
As a store owner,
I want to add items back to inventory when they are returned or exchanged,
so that I can track inventory.

### Acceptance criteria
Scenario 1: Items returned for refund should be added to inventory.
Given that a customer previously bought a black sweater from me
and I have three black sweaters in inventory,
when they return the black sweater for a refund,
then I should have four black sweaters in inventory.

Scenario 2: Exchanged items should be returned to inventory.
Given that a customer previously bought a blue garment from me
and I have two blue garments in inventory
and three black garments in inventory,
when they exchange the blue garment for a black garment,
then I should have three blue garments in inventory
and two black garments in inventory.

## Additional Comments
I have already create a random forest modeling for processed dataset. However, I don't think this random forest model is good because my predicted values have some gaps with real values, and the R-squared is only 0.02. I am also thinking about tuning parameter for random forest based on the current dataset or changing current dataset to get more features for modeling.
