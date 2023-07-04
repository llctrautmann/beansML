Candidate Number: 260072

poetry.toml: provides all the necessary packages for the notebooks to run

# Machine Learning Classification of Turkish Dry Beans

This repository contains a report that analyzes the effectiveness of two different machine learning techniques for classifying Turkish dry beans. The study compared the performance of a multilayer perceptron and boosting algorithms, specifically XGBoost, in achieving high classification scores. The results of this study are presented in contrast to other publications on the topic, and their potential applicability in industrial settings is discussed.

## Introduction

The classification of Turkish dry beans is an important task with various applications in agriculture and food processing. In this study, we investigated the performance of two machine learning methods for accurately classifying different types of dry beans. Specifically, we compared the performance of a multilayer perceptron and a boosting algorithm, XGBoost, in achieving high classification scores.

## Methods

We collected a comprehensive dataset of Turkish dry beans, including various features and corresponding labels indicating the bean types. We then divided the dataset into training and testing sets to evaluate the performance of the machine learning algorithms. 

Two machine learning approaches were implemented: a multilayer perceptron and the XGBoost algorithm. The multilayer perceptron is a neural network-based approach, while XGBoost is a boosting algorithm known for its ability to handle complex datasets.

## Results

Both the multilayer perceptron and XGBoost algorithms outperformed a naive baseline model, demonstrating their effectiveness in classifying Turkish dry beans. However, the boosting algorithm, XGBoost, exhibited superior efficiency and faster runtimes compared to the multilayer perceptron. Consequently, XGBoost emerged as the overall better choice for this classification task.

## Discussion

The results of this study are consistent with prior research on the classification of Turkish dry beans. The use of a boosting algorithm, such as XGBoost, has been shown to yield high classification scores in various applications. Furthermore, the efficiency and faster runtimes of XGBoost make it a viable choice for industrial applications, where computational resources and time constraints are crucial factors.

## Repository Contents

- `data/`: This directory contains the dataset used in the study.
- `notebooks/`: This directory contains Jupyter notebooks with the code used for data preprocessing, model training, and evaluation.
- `results/`: This directory contains the classification results obtained from the experiments.
- `report.pdf`: The detailed report summarizing the study, including methodology, results, and discussion.

## Usage

To reproduce the results of this study or further explore the dataset and methods used, please follow the steps below:

1. Clone this repository:

```
git clone https://github.com/llctrautmann/beansML.git
cd beansML
```

2. Set up the environment by installing the required dependencies:

```
poetry install
```

3. Explore the dataset and preprocess it using the Jupyter notebooks provided in the `notebooks/` directory.

4. Train and evaluate the machine learning models by running the appropriate notebooks.

5. View the classification results obtained in the `results/` directory.

For detailed instructions on using the code and reproducing the study, please refer to the documentation in each notebook.

## Conclusion

This study compared the effectiveness of a multilayer perceptron and the XGBoost algorithm in classifying Turkish dry beans. Both methods outperformed a naive baseline model, but XGBoost demonstrated superior efficiency and faster runtimes. These findings highlight the viability of using boosting algorithms, such as XGBoost, in industrial applications for accurate and efficient classification of Turkish dry beans.

Please refer to the [report.pdf](report.pdf) for a more comprehensive overview of the study and its findings.

## References

Include relevant references and citations to previous studies or works mentioned in the report.

1. Smith, J.
