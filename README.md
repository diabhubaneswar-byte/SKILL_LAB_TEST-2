Project Readme: Loan Default Prediction Model (Revised Architecture)
Introduction
This repository contains the codebase for a Loan Default Prediction Model. This major revision shifts the architecture from a linear, procedural script to a robust Object-Oriented Programming (OOP) structure. This refactoring enhances modularity, maintainability, and code reusability while strictly preserving the model's predictive accuracy.
 Key Architectural Changes
The previous monolithic script is now encapsulated within the LoanDefaultPredictor class. All sequential tasks—from data loading and inspection to preprocessing, training, and subgroup analysis—are now distinct, callable methods.
The core methodology remains a Random Forest Classifier trained on loan data, incorporating StandardScaler for numeric features and OneHotEncoder for categorical features within a standard Pipeline. All hyperparameters and random seeds (random_state=42, max_depth=15) were maintained to ensure the final overall AUC score and subgroup performance metrics remain identical to the original analysis.
The new structure provides a professional, scalable foundation for future enhancements and rigorous performance testing.
