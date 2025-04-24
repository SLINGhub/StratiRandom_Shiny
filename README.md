
# Stratified Randomization Shiny App

This app facilitates stratified randomization using the OSAT package, enabling users to upload CSV files, select covariates. Results and QC plots can be downloaded.

## Online Version of the App
The online version of this app can be access via https://slinghub.shinyapps.io/StratiRandom_Shiny/

## Features

- **CSV Upload**: Upload CSV data files for processing.
- **Covariate Selection**: Choose up to 7 factors for stratification.
- **Batch Configuration**: Set batch numbers; max 96 samples per batch.
- **Randomization & Analysis**: Perform stratified randomization and review p-values.
- **Download Options**: Save randomized data and QC plots.

## Dependencies

This application manages its R package dependencies using renv. To ensure you have all the necessary packages installed in their correct versions, please follow these steps:

`install.packages("renv")`

`renv::restore()`

## How to Use

1. **Upload Data**: Select your CSV file.
2. **Select Covariates**: Define key categorical factors for randomization.
3. **Configure Batches**: Specify batch numbers.
4. **Randomize**: Execute and evaluate results.
5. **Download**: Save output data and plots.

## Additional Information

- Refer to [OSAT documentation](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-13-689) for details.
# RQCee: Evaluation of Response Curves from Preprocessed MS Data

---

Prepare your CSV file correctly to fully utilize the app's capabilities. Happy stratifying!

