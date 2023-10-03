# Market Basket Analysis

### Overview:
This notebook is dedicated to the preprocessing and analysis of the 'Online Retail.xlsx' dataset. The overall flow of the notebook involves importing necessary libraries, loading the dataset, performing initial data analysis, preprocessing the data, and finally, applying some modeling techniques.

### Sections:

1. **Importing necessary Libraries**:
    - Libraries used include:
        - pandas
        - spacy
        - numpy
        - sklearn (specifically AgglomerativeClustering and pairwise_distances)
        - matplotlib
        - fuzzywuzzy
    - Warnings related to a specific message are ignored.

2. **Import Dataset**:
    - The dataset named 'Online Retail.xlsx' is loaded into a DataFrame.
    - Initial checks for missing values are performed.

3. **Data Analysis**:
    - Preliminary analysis of the dataset is carried out.
    - Did exploratory data analysis, statistical summaries, and visualizations.

4. **Data Preprocessing**:
    - The initial step involves removing any null values from the dataset.
    - Further data cleaning, transformation, and preparation steps are likely to follow.

5. **Modelling**:
    - Clustering is applied to the preprocessed data.
    - Utilized Levenshtein similarity and FuzzyWuzzy process libraries

### Dataset:
The dataset used in this notebook is 'Online Retail.xlsx'. Ensure you have this dataset in the appropriate path when running the notebook.
