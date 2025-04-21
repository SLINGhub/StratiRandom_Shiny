
# Stratified Randomization Shiny App

This app facilitates stratified randomization using the OSAT package, enabling users to upload CSV files, select covariates, and optimize experimental setups. Results and QC plots can be downloaded.

## Features

- **CSV Upload**: Upload data files for processing.
- **Covariate Selection**: Choose up to 7 factors for stratification.
- **Batch Configuration**: Set batch numbers; max 96 samples per batch.
- **Randomization & Analysis**: Perform stratified randomization and review p-values.
- **Download Options**: Save randomized data and QC plots.

## Dependencies

Requires R packages:
- **shiny**
- **OSAT**
- **ggplot2**

## How to Use

1. **Upload Data**: Select your CSV file.
2. **Select Covariates**: Define key categorical factors for randomization.
3. **Configure Batches**: Specify batch numbers.
4. **Randomize**: Execute and evaluate results.
5. **Download**: Save output data and plots.

## Additional Information

- Refer to [OSAT documentation](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-13-689) for details.
# RQCee: Evaluation of Response Curves from Preprocessed MS Data

Welcome to **RQCee**, a Shiny application crafted for evaluating response curves from preprocessed mass spectrometry (MS) data. This tool enables users to upload data, visualize plots, and efficiently download analysis results.

## Features

- **Data Upload**: Accepts CSV and TSV files from MRMkit and MH Quant.
- **Plot Layout**: Customizable with user-defined rows and columns.
- **Data Annotation**: Interactive tables for data selection and filtering.
- **Visualization**: Generate and download detailed plots of response curves.
- **Statistics**: Access and export statistical analyses in Excel format.

## Dependencies

The application requires the following R packages:
- **shiny**
- **bslib**
- **shinyjs**
- **rhandsontable**
- **DT**
- **ggplot2**
- **midar**
- **tidyverse**
- **dplyr**
- **stringr**
- **shinyWidgets**
- **openxlsx2**

## How to Use

1. **Select Format**: Choose between MRMkit or MH Quant.
2. **Upload Data**: Upload your MS data files via the sidebar.
3. **Customize Plot Layout**: Set the number of rows and columns for plot arrangement.
4. **Annotate Data**: Use the annotations tab to apply or clear selections.
5. **Retrieve Plots & Statistics**: Navigate the plots and statistics tabs to generate and view results.
6. **Download Results**: Export plots as PDFs and statistics as Excel files.

## Additional Information

- RQCee offers a user-friendly interface for comprehensive MS data analysis, ensuring intuitive data processing and result accessibility.
- For further assistance or inquiries, please contact the development team: Shanshan Ji (lsijish@nus.edu.sg) or Bo Burla (bo.burla@nus.edu.sg).

---

Ensure your data is formatted correctly to fully utilize RQCee's capabilities. Happy analyzing!
---

Prepare your CSV file correctly to fully utilize the app's capabilities. Happy stratifying!

