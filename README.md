# Progress Report 2

## Title 1
 t  sFind

### Narrative
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


Acceptance criteria
    A description of each specific scenario of the narrative with the following structure:

        Given: the initial context at the beginning of the scenario, in one or more clauses;
        When: the event that triggers the scenario;
        Then: the expected outcome, in one or more clauses.

## Title 2
Visualizing features of datasets

### Narrative
1.	Observe feature characteristic, 2check is there any problems within the datasets
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

## Title 3
Random Forest modeling

### Narrative
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
