# Tornado Trend Analysis

**Group Leader**: Chris Woods  
**Group Members**: Zaid Fada, Malek Thabet  
**Course**: DS 4002  
**Date**: 25 October 2024

## Project Overview

This repository contains the code, data, and documentation for our project analyzing tornado trends in the U.S. from 1998 to 2023. Our aim is to build a time-series prediction model using ARIMA and SARIMA to forecast tornado-related metrics like property damage, fatalities, and frequency. By focusing on minimizing the Mean Absolute Error (MAE), we will identify the most effective prediction model for these metrics, contributing to a better understanding of long-term trends and improving disaster response strategies.

## Repository Structure

- **README.md**: Provides an overview and instructions for reproducing the results.
- **LICENSE.md**: License for the project (MIT License).
- **requirements.txt**: Python packages needed for the project
- **SCRIPTS/**: Contains the Python scripts for data processing, feature engineering, and model training.
- **DATA/**: Contains the dataset used for training and testing.
- **OUTPUT/**: Stores the results, including figures and tables from the analysis.

```bash
.
├── README.md                # Project overview and instructions
├── LICENSE.md               # License information (MIT)
├── requirements.txt         # Python packages needed for the project
├── SCRIPTS/
│   ├── exploratoryplots.ipynb  # Prelim data discobvery
│   └── analysis.ipynb       # Detailed step-by-step analysis performed
├── DATA/
│   └── Data.md              # Steps to download dataset
├── OUTPUT/
│   ├── model_results.md    # Accuracy, confusion matrix, and classification report
│   └── plots/              # Figures generated during prelim data discovery
```

## Software and Platform

- **Programming Language**: Python
- **Packages Required**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `seaborn`
  - `matplotlib`
  - `wordcloud`
- **Platform**: Windows, macOS, or Linux

## Data

The dataset for this project is sourced from the "NCDC Storm Events Database" and includes comprehensive tornado event data across the U.S. from 1998 to 2023. It contains information such as the date, location, injuries, fatalities, and property damage for each tornado event.

## Instructions for Reproducing Results

1. Clone this repository:

   ```bash
   git clone [repository link]
   cd [repository directory]
   ```

2. Install the required Python packages: Ensure that Python 3.x is installed. Then, install the necessary packages by running:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and prepare the data:

   - Go to the `Data.md` and follow the steps to download our data
   - Place the dataset in the `DATA/` folder

4. Run the analysis:

   - Go to `/SCRIPTS/analysis.ipynb`, follow the comments in the cells and run each cell to perform our analysis!

5. Review the results:
   - The model’s accuracy, precision, recall, and other performance metrics will be saved in the [models_results.md](OUTPUTS/models_results.md) file
   - Visualizations will be saved in the `OUTPUTS/plots/` directory.
