
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

---

Prepare your CSV file correctly to fully utilize the app's capabilities. Happy stratifying!

