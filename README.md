# UCB-ML-AI-Capstone-Project

Leslie K. English

UC Berkeley Professional Certificate in Machine Learning and Artificial Intelligence

GitHub.com Repository: https://github.com/LeslieSeattle/UCB-ML-AI-Capstone-Preliminary

Summary of Capstone Project: 

In 2023, a team of University of Washington, Seattle (UW) researchers and Seattle-area scientists published a paper titled “ExplaiNAble BioLogical Age (ENABL Age): an artificial intelligence framework for interpretable biological age” (The Lancet Healthy Longevity, Volume 4, Issue 12, E711-E723, December 2023, Open Access. Wei Qiu, MSca ∙ Hugh Chen, PhDa ∙ Prof Matt Kaeberlein, PhDb ∙ Prof Su-In Lee, PhDa  ∙ https://www.thelancet.com/journals/lanhl/article/PIIS2666-7568(23)00189-7/fulltext) to explain the artificial intelligence model they built to create an age clock that can estimate a person’s biological age based upon medical, health, and lifestyle data provided by the person. The UW model used twenty features selected from approximately a thousand available features in the UK Biobank and National Health and Nutrition Examination Survey (NHANES) datasets. 

This UCB capstone project is to return to the original databases used in the UW model, and build a new ML/AI model with a different combination of twenty features, to determine if a more accurate age clock can be created.

The new models removed from the NHANES Dataset all features that derived from non-laboratory data such as Questionnaires, Demographics, and Physical Examinations.

Selection of laboratory blood bio marker features was performed using two different machine learning methods. Surprisingly, for all newly compiled combinations of laboratory features, across all models that were trained on the data, the models performed less well on just the laboratory data than they did on the range of features selected by the UW team.

The datasets are larger than what GitHub will allow to be uploaded.
