Use numeric prediction techniques to build a predictive model for the dataset.
This dataset is provided on the course website and contains data about whether or not different consumers made a purchase in response to a test mailing of a certain catalog and, in case of a purchase, how much money each consumer spent. The data file has a brief description of all the attributes in a separate worksheet. Note that this dataset has two possible outcome variables:
`Purchase` (0/1 value: whether or not the purchase was made) and `Spending` (numeric value: amount spent).

Your tasks:
(a) Build numeric prediction models that predict Spending based on the other available customer information. Use linear regression, k-NN, regression tree, SVM regression and Neural Network and ensembling models.
Briefly discuss your explorations and present the best result (best predictive model) for each of the three techniques. Compare the techniques; which of them provides the best predictive performance? Please make sure you use best practices for predictive modeling. (I.e., do you need to set which hyper-parameter? Normalize? Feature Selection? Etc.)

(b) As a variation on this exercise, create a separate “**restricted**” dataset, which includes only purchase records (i.e., where Purchase = 1). Build numeric prediction models to predict Spending for this restricted dataset. All the same requirements as for task (a) apply.

(c) For each predictive modeling technique, discuss the predictive performance differences between the models built for task (a) vs. task (b): which models exhibit better predictive performance? Why do you think that is?
