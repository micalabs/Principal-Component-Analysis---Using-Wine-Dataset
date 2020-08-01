# Principal-Component-Analysis---Using-Wine-Dataset

# Principal Component Analysis with Python
Principal Component Analyis is basically a statistical procedure to convert a set of observation of possibly correlated variables into a set of values of linearly uncorrelated variables. Each of the principal components is chosen in such a way so that it would describe most of the still available variance and all these principal components are orthogonal to each other. In all principal components first principal component has maximum variance.

# Uses of PCA:
It is used to find inter-relation between variables in the data. It is used to interpret and visualize data. As number of variables are decreasing it makes further analysis simpler. It’s often used to visualize genetic distance and relatedness between populations.

The dataset used for implementation of PCA can be found in this link - https://media.geeksforgeeks.org/wp-content/uploads/Wine.csv and https://archive.ics.uci.edu/ml/datasets/wine

# Data Set Information:
These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

I think that the initial data set had around 30 variables, but for some reason I only have the 13 dimensional version. I had a list of what the 30 or so variables were, but a.) I lost it, and b.), I would not know which 13 variables are included in the set.

The attributes are (dontated by Riccardo Leardi, riclea '@' anchem.unige.it )

- Alcohol
- Malic acid
- Ash
- Alcalinity of ash
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- OD280/OD315 of diluted wines
- Proline

In a classification context, this is a well posed problem with "well behaved" class structures. A good data set for first testing of a new classifier, but not very challenging.
