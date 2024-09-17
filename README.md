# Data-visualization
Iris Dataset Visualization
This repository contains various data visualizations and statistical plots created using Python's matplotlib and seaborn libraries to explore the famous Iris dataset. These plots help in understanding the relationships between the features and the distribution of species within the dataset.

Overview

The Iris dataset contains 150 observations of iris flowers, with four features for each flower: sepal length, sepal width, petal length, and petal width. The dataset is widely used for pattern recognition and classification tasks, as it includes three distinct species: Setosa, Versicolor, and Virginica.

Visualizations
1. Pair Plot of Iris Dataset

A pair plot is used to visualize pairwise relationships between the four numerical features. It helps in identifying correlations and patterns among the different species.

Code: sns.pairplot(iris, hue='species', height=2.5)

Purpose: To visually compare how the species differ based on the sepal and petal measurements.

2. Pie Plot for Species Frequency
   
This pie chart shows the distribution of the three species (Setosa, Versicolor, Virginica) in the dataset.

Code: plt.pie()

Purpose: To visually display the proportion of each species in the dataset.

3. Scatter Plot: Sepal Length vs Sepal Width
   
A scatter plot illustrating the relationship between sepal length and sepal width, color-coded by species.

Code: sns.scatterplot()

Purpose: To visualize how the sepal measurements vary across species.

4. Histogram Grid: Distribution of Sepal and Petal Features
   
This grid of histograms shows the distribution of the four features (sepal length, sepal width, petal length, petal width) with KDE (Kernel Density Estimate) overlay.

Code: sns.histplot()

Purpose: To understand the spread and distribution of each feature in the dataset.

5. Jointplot: Sepal Length vs Sepal Width
   
A jointplot showing the relationship between sepal length and sepal width with marginal histograms.

Code: sns.jointplot()

Purpose: To combine the scatter plot with histograms for a deeper look at bivariate relationships.

6. KDE Plot: Sepal Length vs Sepal Width (Setosa)
   
A KDE plot for the Setosa species, illustrating the density of sepal length and sepal width values.

Code: sns.kdeplot()

Purpose: To visualize where the Setosa species' sepal measurements are concentrated.

7. KDE Plot: Petal Length vs Petal Width (Setosa)
   
Similar to the previous KDE plot, this one focuses on the petal length and petal width for Setosa.

Code: sns.kdeplot()

Purpose: To observe the concentration of petal measurements for the Setosa species.

Dependencies

Make sure you have the following Python libraries installed to run the code:

matplotlib

seaborn

pandas (for dataset handling, if required)

You can install these dependencies using pip:

pip install matplotlib seaborn pandas

Dataset

The Iris dataset is a well-known dataset in the machine learning community, available through the seaborn library:

import seaborn as sns
iris = sns.load_dataset('iris')
The dataset includes the following columns:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
Species (Setosa, Versicolor, Virginica)

Acknowledgements

The Iris dataset was introduced by British biologist and statistician Ronald Fisher in his 1936 paper, "The use of multiple measurements in taxonomic problems."

Visualization libraries used: seaborn, matplotlib.

Prepared by : Paila Rakesh

linkedin profile : www.linkedin.com/in/rakesh-paila-b4a473309

Gmail : pailarakesh004@gmail.com
