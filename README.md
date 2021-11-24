# COVID-19-Resources-prediction
Covid-19 Resources Predictions
In this project, the three major Objective of the Project:
● Prediction of final outcome of the patient(Death/Discharged).
● Duration of Hospitalization.
● ICU Requirement.

Conclusion:
Since almost all features for our Covid-19 outcome prediction task were of the
categorical type(except age), the analysis has been planned accordingly. We used the
insights gained from visualizations and statistical analysis for primary understanding on
the dataset. Modelling is initiated with some naive algorithms and finally adopted
Xgboost Model, it successfully satisfied our objective of prediction of correct outcome of
the patients along with a uniformly distributed recall, in a robust manner. The Model,
though satisfying our objective efficiently, is unable to cross a certain ~0.85 mark
despite exhaustive hyperparameter tuning, which is an indicator that the given features
of the dataset are not capable enough to dictate outcome alone and demand more
impactful attributes, for instance, incorporation of Laboratory test parameters(e.g, CRP,
Ferritin, D-Dimer etc) would improve the result and along with this, keeping in mind, the
imbalancing dataset wrt death cases(which it will be always), more training data will also
help to apply more robust algorithm though Deep NeuralNet architectures
