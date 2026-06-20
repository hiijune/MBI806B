\# Iris Dataset - Class Distribution Visualization



\## Description

This project visualizes the number of samples per class in the classic Iris dataset using Python (pandas + matplotlib).



\## Steps

1\. Loaded the Iris dataset (`iris.data`) using pandas.

2\. Counted the number of samples for each species (setosa, versicolor, virginica).

3\. Visualized the class distribution using a bar chart.



\## Result

| Species    | Count |

|------------|-------|

| setosa     | 50    |

| versicolor | 50    |

| virginica  | 50    |



!\[Class Distribution](class\_distribution.png)



\## Insight

The dataset is \*\*perfectly balanced\*\* — each of the three classes contains exactly 50 samples, with no class dominating the dataset. This is uncommon in real-world data, where class imbalance is typical. A balanced dataset like this is ideal for classification tasks since model accuracy won't be biased toward a majority class.

