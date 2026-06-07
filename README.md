
# Iris-Exploratory-Data-Analysis

### 📌 Project Overview & Task Objective:
`Iris_analysis.ipynb` performs an exploratory data analysis and visualization of the famous Iris dataset. The primary objective of this task was to 
perform a comprehensive exploratory data analysis (EDA) on the Iris dataset. This involved understanding the dataset's structure, identifying key
characteristics, and visualizing relationships between different features to gain insights into the distribution and separation of the three Iris species.

### 📊 Dataset Information:
The Iris dataset is a classic and very easy multi-class classification dataset. It consists of
150 samples from three species of Iris flowers (Iris setosa, Iris virginica, and Iris
versicolor). Four features were measured from each sample: the length and the width of
the sepals and petals.
 - **Samples**: 150
 - **Species**: 3 (setosa, versicolor, virginica)
 - **Features**:
    - `sepal_length (cm)`
    - `sepal_width (cm)`
    - `petal_length (cm)`
    - `petal_width (cm)`
  
 - **Target**: `species`
 
### 🧩 Features
 - Loading the Iris dataset using Seaborn.
 - Displaying the shape, columns, and first few rows of the dataset.
 - Providing a summary of the dataset's structure and basic statistics.
 - Visualizing relationships between different variables using scatter plots and pair plots.

### ⚙️ Installation
To run this notebook locally, you will need to have Python installed along with the
following libraries. You can install them using pip:

- `pip install pandas numpy scikit-learn seaborn matplotlib`

### 🔍 Approach
My approach to analyzing the Iris dataset involved the following steps:
- **Library Import:** Imported essential Python libraries for data manipulation (pandas, numpy),
    machine learning (scikit-learn), and visualization (seaborn, matplotlib).
- **Data Loading:** Loaded the `Iris dataset` directly using `Seaborn's` built-in
    load_dataset function, which provides a clean and readily available version of the
    dataset.
- **Data Inspection:** Performed initial data inspection to understand its structure. This
    included:
  - **Checking the shape of the dataset** (`iris_dataset.shape`)  
    - Determines the number of rows (samples) and columns (features).
  - **Listing the column names** (`iris_dataset.columns.tolist()`)  
    - Identifies the features and the target variable.
  - **Viewing the first five rows** (`iris_dataset.head()`)  
    - Provides a glimpse of the data format and sample values.
  - **Obtaining a summary of the dataset** (`iris_dataset.info()`)  
    - Shows data types, non-null counts, and memory usage.
  - **Generating descriptive statistics** (`iris_dataset.describe()`)  
    - Offers insight into central tendency, dispersion, and distribution shape for numerical features.

- **Data Visualization** : Utilized various plotting techniques to visualize the
    relationships between variables and the distribution of species:
  - **Scatter Plots**: Created scatter plots to observe the relationships between
             pairs of features (e.g., sepal length vs. sepal width, petal length vs. petal
             width). These plots were crucial for identifying potential correlations and how
             well the different species are separated based on these features.
  - **Pair Plots**: Generated pair plots using Seaborn, which provide a matrix of
             scatter plots for all possible pairs of features, along with histograms or kernel
             density estimates for individual features. This gave a comprehensive overview
             of the dataset's multivariate relationships and helped in visually
             distinguishing the Iris species.
This systematic approach allowed for a thorough understanding of the dataset's
characteristics and the relationships between its features, which is fundamental for any
subsequent machine learning tasks.

## 💻Technologies Used
- **P Y T H O N**
- **P A N D A S**
- **N U M P Y**
- **S C I K I T - L E A R N**
- **S E A B O R N**
- **M A T P L O T L I B**

## 📈 Results and Insights
The analysis of the Iris dataset yielded several key insights:
  - **Distinct Species Separation**: The visualizations, particularly the scatter plots and
    pair plots, clearly demonstrated that the Iris Setosa species is well-separated from
    Iris Versicolor and Iris Virginica based on petal length and petal width. This
    suggests that these two features are highly effective in distinguishing Setosa from
    the other two species

  - **Overlap Between Versicolor and Virginica**: While Setosa was clearly distinct,
    there was some overlap between Iris Versicolor and Iris Virginica, especially when
    considering sepal length and sepal width. This indicates that classifying these two
    species might be more challenging and could require more sophisticated models
    or a combination of features.
    
  - **Feature Importance**: Petal length and petal width appear to be the most
    discriminative features for classifying the Iris species. Sepal length and sepal width,
    while still useful, showed less clear separation between the species.
    
  - **Data Quality**: The info() output confirmed that there were no missing values in
    the dataset, indicating high data quality and no need for imputation.
    
  - **Statistical Overview**: The describe() method provided a quick statistical
    summary, revealing the range, mean, and standard deviation for each numerical
    feature, which helps in understanding the spread and central tendency of the data.
    
Overall, the exploratory data analysis provided a strong foundation for understanding
the Iris dataset, highlighting the most important features for classification and the
inherent separability of the different Iris species. These insights are crucial for guiding
the selection and development of appropriate machine learning models for
classification tasks.

## ▶️ Usage
- Clone the repository: bash git clone `https://github.com/Shilpachhatani/Iris-Exploratory-Data-Analysis.git`
- Navigate to the project directory: `bash cd Iris-Dataset-Analysis`
- Open the Jupyter Notebook: `bash jupyter notebook Iris_analysis.ipynb`
- Run the cells in the notebook to see the analysis and visualizations.

## 📊 Visualizations
The notebook includes various visualizations to understand the dataset better, such as:
- `Scatter plots` to show relationships between different variables.
- `Pair plots` for a comprehensive view of all feature relationships.
  
## 🤝 Contributing
Contributions are welcome! If you have any suggestions or improvements, please open
an issue or submit a pull request.

## 📬 Contact
For questions or collaboration:
- GitHub: `Shilpachhatani`
- Email: `shilpachhatani669@gmail.com`
