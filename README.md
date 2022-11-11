# Progress Report 2

## Title 1
Find an appropriate modeling for UKBioBank.

### Narrative
As a researcher who want to use UKBioBank database to do research frequently in the future,
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
Discover relationships between head motions and mental states

### Narrative
As a doctor or a researcher,
I want to know a person's mental state,
so that I can input the corresponding head motions into modeling and predict his or her mental state.

### Acceptance criteria
Scenario 1: The person is not in a good state of mind and is most likely to be depressed.
Given that a person takes a Magnetic resonance imaging exam
and gets some phenotypes of brain such as mean FA in cingulum hippocampus on FA skeleton,
when we get more than 300 features and predict this person's mental state based on our appropriate modeling,
then we should conclude it is most likely this person is in a bad state of mind.

Scenario 2: The person is in a good state of mind.
Given that a person takes a Magnetic resonance imaging exam
and gets some phenotypes of brain,
when we get more than 300 features and predict this person's mental state based on the model,
then we should conclude it is most likely this person is in a good state of mind.


## Additional Comments
I have already create a random forest modeling for processed dataset. However, I don't think this random forest model is good because my predicted values have some gaps with real values, and the R-squared is only 0.02. I am also thinking about tuning parameter for random forest based on the current dataset or changing current dataset to get more features for modeling. For next step, I think I need to observe features' characteristics based on some visualizations and to think more about features I choose for modeling.
