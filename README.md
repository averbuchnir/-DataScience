
# Personal Portfolio for Data Science

This repository showcases various data science skills and techniques that I, as a Ph.D. in Data Science, have acquired and applied throughout my career. The code and examples presented here highlight my proficiency in Python for data manipulation, visualization, and advanced analytics.

## Table of Contents (Portfolio)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview
This repository contains Jupyter Notebooks demonstrating various data science techniques, including data visualization, 3D graphing, and data interpolation, using Python. Each notebook is designed to showcase specific skills and methodologies in data science, reflecting the breadth of knowledge from my Ph.D. studies.

## Installation
To run the notebooks, you will need to have Python installed on your system. Once you have Python set up, you can install the required dependencies by running the following command:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

## Usage
After installing the dependencies, you can explore the Jupyter Notebooks in the repository. Open the notebooks in Jupyter Lab or Jupyter Notebook by navigating to the directory and running:

\`\`\`bash
jupyter notebook
\`\`\`

Once the notebook server starts, you can select the notebook you want to explore from the list.

## Dependencies
The following Python libraries are required to run the notebooks in this repository:

- pandas==2.2.2
- pytz==2024.1
- matplotlib==3.8.4
- seaborn==0.13.2
- plotly==5.22.0
- numpy==1.26.4
- ipywidgets==7.8.1

These dependencies are listed in the \`requirements.txt\` file, and you can install them using the command provided in the [Installation](#installation) section.

## Contributing
At this time, no contributions are being accepted for this project. However, feel free to fork the repository and modify it for your own use.

## License
This project is not licensed under any specific open-source license.

---

# LSTM Model Section

This section of the repository demonstrates the use of Long Short-Term Memory (LSTM) models for time series forecasting.

## Table of Contents (LSTM)
- [LSTM Model Overview](#lstm-model-overview)
- [Data Sources](#data-sources)
- [LSTM Example Notebook](#lstm-example-notebook)
- [Creating a Conda Environment](#creating-a-conda-environment)
- [Dependencies (LSTM)](#dependencies-lstm)

---

## LSTM Model Overview
In this section, I showcase how to build an LSTM model for time series forecasting using Python. The model is designed to predict future data points based on historical trends in the dataset.

## Data Sources
The LSTM model is based on the following key files:
1. **\`sample_DATA_LSTM.csv\`**: Contains the time-series dataset used for training and testing the LSTM model.
2. **\`LSTM_example(GridSearch).ipynb\`**: A Jupyter Notebook that explains how to build and fine-tune the LSTM model, including hyperparameter tuning via GridSearch.
3. **\`LSTM_requiremnt.txt\`**: A file listing all the necessary dependencies to run the LSTM example.

## LSTM Example Notebook
After setting up the required environment (see the next section), you can run the LSTM model example in the Jupyter Notebook \`LSTM_example(GridSearch).ipynb\`. This notebook includes all the steps for building, training, and evaluating the LSTM model.

## Creating a Conda Environment
To avoid conflicts with other Python packages, it’s recommended to create a separate Conda environment for running the LSTM model. You can do this as follows:

1. **Create the environment**:
   \`\`\`bash
   conda create --name LSTM python=3.8
   \`\`\`

2. **Activate the environment**:
   \`\`\`bash
   conda activate LSTM
   \`\`\`

3. **Install dependencies**:
   After activating the environment, install the dependencies by running:
   \`\`\`bash
   pip install -r LSTM_requiremnt.txt
   \`\`\`

## Dependencies (LSTM)
The LSTM section requires the following Python libraries to be installed:

- numpy==1.24.2
- pandas==2.0.1
- plotly==5.11.0
- scikit-learn==1.1.2
- tensorflow==2.9.0
- matplotlib==3.5.2
- multiprocessing==0.70.13

These dependencies are listed in the \`LSTM_requiremnt.txt\` file and can be installed using the instructions in the [Creating a Conda Environment](#creating-a-conda-environment) section.
