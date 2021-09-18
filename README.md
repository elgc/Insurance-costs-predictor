# Insurance-costs-predictor

Many factors affect how much you pay for health insurance are not within our control. Kaggle presents a small file with some factors that affect how much health insurance premiums cost

- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest

I have previously done exploratory analysis on this data for a webinar in regression analysis at ISSSP (International society of Six Sigma Professionals). It was found that the most influential factor is smoking.

To increase the performance of a model used to forecast cost of insurance I developed eight models that included:

- Multiple linear regression. The **Baseline model** with **R2=0.75**
- Multiple linear regression with transformed **y**: with **R2=0.77**
- Random Forest Tree with Hyperparameter Optimization: with **R2=0.87** Best model.
- Random Forest Tree with Hyperparameter Optimization: with **R2=0.82**
- Second order Polynomial Regression (Kaggle selected in example): with **R2=0.80**
- Random Forest of Second Order Poly Reg with Hyper Opt: **R2=0.87**

All values of R2 correspond to the model evaluated on the test set. 

The model selected provides good working predictability.

Reference: https://www.kaggle.com/mariapushkareva/medical-insurance-cost-with-linear-regression
