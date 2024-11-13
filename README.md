# Analyzing Doxorubicin and Cardioprotective PLGA Nanoparticles on Murine Cardiomyocytes using Machine Learning Modeling to Mitigate Cardiotoxicity
## Contents
1. [Overview](#project-ideation)
2. [Repository Contents](#repository-contents)
3. [Download Paper](#download-conference-paper)
4. [Citation](#citation)

## Project Ideation
Using machine learning modeling, we created a random forest model for processing characteristics of murine cells to predict which of the three treatments it received. We perform feature engineering utilizing correlation matrices between the features, Variation Inflation Factor (VIF) scores, and their Permutation Importance (PI) scores.

## Repository Contents
[Full Project Source Code](https://github.com/christinlee367/PLGA/blob/main/Project/PLGAShared.ipynb)
- This .ipynb includes preprocessing, fine tuning, and machine learning modeling that we did to reach our final model.
- **Preprocessing**: Reading the data, Outlier Removal, Finding correlation, Boxplots of Features, and Histograms of Features.
- **Fine-Tuning the Data**: Combining three treatment datasets, PCA Comparison, Randomized Search for Random Forests, Permutation Importance, VIF scores, and Refining full dataset.
- **Machine Learning Modeling**: Random Forest Model for Classification, Accuracy on Random Forest Model, Visualizing decision trees, comparing alternative models.

[Datasets](https://github.com/christinlee367/PLGA/tree/main/Data)
- The data is composed of 17 murine cell characteristics and administered different treatments of DOX, DOX with PLGA, and kept untreated cells for control.
- Each treatment is separated in a *.xlsx file. _data_dox_plga.xlsx_ for DOX + PLGA treated cells, _data_dox.xlsx_ for DOX treated cells, and _data_untreated.xlsx_ for Untreated cells(control variable). 

[Graphs](https://github.com/christinlee367/PLGA/tree/main/Figures)
- contains the graphs in \*.svg files, ran from the Full Project Source Code, that are used in the final conference paper. 

## Download Conference Paper
PDF Document: [PLGA2024MABM.pdf](https://github.com/user-attachments/files/17709780/PLGA_V4_.pdf)

Word Document: [PLGA2024MABM.docx](https://github.com/user-attachments/files/17709806/PLGA_V4_.docx)

## Citation
C. Lee, J. McCreary, M. Chen, H. Chen, and J. Manjarrés. “Analyzing Doxorubicin and Cardioprotective PLGA Nanoparticles on Murine Cardiomyocytes using Machine Learning Modeling to Mitigate Cardiotoxicity.” _2024 IEEE International Conference on Bioinformatics and Biomedicine_, (2024).
