
# Project Title
Transcriptomic Analysis and Predictive Modeling of NR8383 Macrophage Response to TiO2 Exposure

## Description
This project involves the analysis of gene expression data from NR8383 rat macrophage cells after exposure to TiO2 nanoparticles (specifically the NRCWE001 variant). The aim is to identify differentially expressed genes and understand the biological pathways associated with nanomaterial toxicity. 

## Dataset Summary
- **Title**: Transcriptomic study of NR8383 rat macrophages cells following exposure to TiO2 (NRCWE001).
- **Accession Number**: GSE156564
- **Public Release Date**: August 18, 2023
- **Submission Date**: August 20, 2020
- **Last Update Date**: August 18, 2023
- **Study Summary**: Microarray analyses were performed to detect differentially expressed genes in response to TiO2 exposure, funded by the European Union's Horizon 2020 research program.
- **Design**: Gene expression levels were compared between control cells and those exposed to 3 cm²/cm² of TiO2 for 4 hours, with four biological replicates for each condition.
- **Data Type**: Expression profiling by array.
- **Contributors**: Zahra Doumandji, Romain Schmitt.

## Methodology
- **Preprocessing**: The raw data was preprocessed to filter out non-expressive or noisy signals. The preprocessing steps included normalization, transformation, and summarization.
- **Feature Selection**: Recursive Feature Elimination (RFE) was used to select the most predictive features for the machine learning model.
- **Model Training**: A Support Vector Regression (SVR) model was trained to predict the response variable, which is presumably a score indicating differential expression or a related biological metric.
- **Evaluation**: The model was evaluated using Root Mean Squared Error (RMSE) and cross-validation to assess its predictive performance.

## Results
- Briefly summarize the RFE results, the features selected, and the performance metrics of your model.

## Repository Structure
```
/GSE156564_Transcriptomic_Analysis
|-- /data
|   |-- GSE156564_Processed_data_NRCWE001.xlsx
|   |-- GSE156564_series_matrix.txt
|
|-- /notebooks
|   |-- data_preprocessing.ipynb
|   |-- feature_selection.ipynb
|   |-- model_training.ipynb
|
|-- /src
|   |-- data_preparation.py
|   |-- feature_engineering.py
|   |-- model.py
|
|-- README.md
|-- requirements.txt
```

## README.md
Your README file should include the following sections:
- **Project Title**
- **Abstract**: A brief summary of your project.
- **Installation**: Instructions on setting up the project environment.
- **Usage**: How to run your scripts or notebooks.
- **Data**: An explanation of the data files and their sources.
- **Methodology**: A detailed description of your analysis steps.
- **Results**: An overview of the results and findings.
- **Contributing**: Guidelines for contributing to the project.
- **License**: The license under which your project is released.
- **Contact**: How to reach you for further information or collaboration.

## Requirements.txt
This file should list all the Python libraries and their versions needed to run your project.

## Contributing Guidelines
Detail how others can contribute to your project. Include instructions for forking the repository, making changes, and making a pull request.

## License
Include a license for your project. Open-source projects often use licenses like MIT, GPL, or Apache 2.0.

## Contact Information
Provide your contact information or the best way to reach you for collaboration or questions about the project.

Remember to push all changes to your GitHub repository and maintain it with the latest versions of your project files.
