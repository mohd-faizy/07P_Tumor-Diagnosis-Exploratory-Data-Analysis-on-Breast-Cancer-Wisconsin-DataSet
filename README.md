[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/ansicolortags.svg)](https://www.python.org/downloads/)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://github.com/mohd-faizy/07P_Exploratory_Data_Analysis_With_Seaborn/blob/master/LICENSE)
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://opensource.com/resources/what-open-source)


# __Tumor Diagnosis: Exploratory Data Analysis With Seaborn__

<img src="https://github.com/mohd-faizy/07P_Exploratory_Data_Analysis_With_Seaborn/blob/master/Proj_img/01.png">

## __DataSet__

The [Breast Cancer Diagnostic data](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) is available on the UCI Machine Learning Repository. This database is also available through the [UW CS ftp server](http://ftp.cs.wisc.edu/math-prog/cpo-dataset/machine-learn/cancer/WDBC/).

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].


> _Producing visualizations is an important for exploring and analyzing real-world data sets. Visualization is an indispensable method in any data scientist's toolbox. In this Project we will employ the statistical data visualization library, Seaborn, to discover and explore the relationships in the __Breast Cancer Wisconsin (Diagnostic) Data Set__ &  Exploratory data analysis (EDA) using visualizations to identify and interpret inherent relationships in the data set, produce various chart types including histograms, violin plots, box plots, joint plots, pair grids, and heatmaps, customize plot aesthetics and apply faceting methods to visualize higher dimensional data._

## Objectives
    
- Produce data visualizations with Seaborn on Breast Cancer Diagnostic data.
- Apply graphical techniques used in exploratory data analysis (EDA).
- Use differenting Machine Learning Algorithms like __KNN's, PCA, RF & SVM__ for predicting the outcome.

## Project Structure

#### :zero::one: Introduction and Importing the Data

- In this task, we are introduced to the project and learning outcomes.
- Once we are familiarized with the Rhyme interface, we begin working in Jupyter Notebooks, a web-based interactive computational environment for creating notebook documents.
- Next, we will import essential libraries such as NumPy, pandas, Seaborn, and matplotlib.
- Lastly, we use pandas to load the Breast Cancer Wisconsin (Diagnostic) [Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

#### :zero::two: Separate Target from Features

- Now that the data set is in memory, we can explore the characteristics of its attributes and instances.
- We will drop columns that cannot be used for analysis and classification.
- Note that this does not constitute feature selection. We are dropping columns that have no bearing on the analysis we will be conducting, and will instead clutter our analysis. After producing descriptive statistics about the data, we will separate the target from the features.
- The target contains the diagnosis with binary class labels, M or B, for malignant and benign tumors respectively. 

#### :zero::three: Diagnosis Distribution Visualization

- A very common question during model evaluation is, "Why isn't the model I've picked predictive?". Most often, it is a result of a class imbalance.
- In this task, we will use Seaborn's countplot() method to visualize the target distributions.
- We will also generate descriptive statistics about the features that summarize the central tendency, dispersion and shape of the data set's distribution.

#### :zero::four: Visualizing Standardized Data with Seaborn

- As the columns in the data set take on values of varying range, we need to standardize the data before proceeding with further analysis and visualization.
- To begin feature analysis, we use Seaborn's violinplot() method. Violin plots are similar to box plots, except that they also show the probability density of the data at different values, usually smoothed by a kernel density estimator. 

#### :zero::five: Violin Plots and Box Plots

- We are using violin plots and box plots to identify features that best separate the data for classification.
- Box plots are especially useful in identifying outliers in the data.
- Using violin plots, we are also able to infer whether certain features are correlated.
- To minimize clutter in our visualizations, we divide the features into three batches of ten features and produce separate plots for them.

#### :zero::six: Using Joint Plots for Feature Comparison

- Joint plots come in handy to illustrate the relationship between two features.
- We will use seaborn's jointplot() method to draw a scatter plot with marginal histograms and kernel density fits. We can examine the relationship between any two features using the Pearson correlation coefficient of the regression through our scatter plot.

#### :zero::seven: Observing the Distribution of Values and their Variance with Swarm Plots

- We have learned that violin plots are a great tool for visualizing sparse distributions. As our data set contains close to 600 rows, we might want to simply display each point in the same visualization.
- This need is satisfied by Seaborn's swarmplot() method. A swarm plot can be drawn on its own, but it is also a good complement to a box or violin plot in cases where you want to show all observations along with some representation of the underlying distribution.

#### :zero::eight: Observing all Pairwise Correlations

- A good way to identify correlations between features is to visualize the correlation matrix as a heatmap.
- We will make a note of the correlated features so that we can drop them from our data set before building a predictive model in the next project.
- In the next project, we will remove these correlated features and analyze the classification accuracy we get using XGBoost, a boosted decision tree classifier. We will then employ various feature selection and feature extraction methods to get the most predictive features and improve our classification accuracy.



### Connect with me:


[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][StackExchange AI]

[twitter]: https://twitter.com/F4izy
[linkedin]: https://www.linkedin.com/in/faizy-mohd-836573122/
[StackExchange AI]: https://ai.stackexchange.com/users/36737/cypher


---


![Faizy's github stats](https://github-readme-stats.vercel.app/api?username=mohd-faizy&show_icons=true)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mohd-faizy&layout=compact)](https://github.com/mohd-faizy/github-readme-stats)
