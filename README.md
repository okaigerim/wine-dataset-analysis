# wine-dataset-analysis

## Project Execution Report

### 1.	Introduction: Part 1

A brief description of the selected dataset and the task to be solved:

Dataset: “Combined-wine”

Link: https://www.kaggle.com/datasets/siyuanh/combined-wine-data

Two datasets were created, using red and white wine samples. The inputs include objective tests (e.g. PH values) and the output is based on sensory data.

Task: **classification**. According to the data on the content of several data mining methods were applied to model these datasets under a regression approach. The support vector machine model achieved the best results.

### 2.	The Main: Part 2
Description of the results achieved:

Training the 3 classification models and using linear classifier with results metrics(f1-score=0.99), the support vector machine with results metrics(f1-score =0.99 ) and decision tree with results metrics(f1-score = 1 ). The model trained using the decision tree showed the best quality.

Description of the progress of the case task:

Stages of the project:
- loading the dataset;
- studying the dataset;
- data cleaning;
- training of classification models;
- evaluation of the quality of trained classification models;
- choosing the best model.

Description of deviations and difficulties encountered during the task, as well as the ways used to overcome them:
In the task we have  incorrect values were found in the dataset ("#NUM!" where the numbers should be). Rows with incorrect values have been deleted from the dataset.

### 3.	Conclusion.

Conclusions on the work done.

In the project, we realized the selected 3 classification models which of trained, and get the best one with using quality metrics.

### 4.	Literature.

List of used literature:
- Aurélien Géron. Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, Second Edition. O’Reilly Media. 2019.
- Jake VanderPlas. Python Data Science Handbook. O'Reilly Media, Inc. 2016.
- Luca Massaron, John Paul Mueller. Python for Data Science For Dummies. John Wiley & Sons, Inc. 2015.
- scikit-learn Tutorials: https://scikit-learn.org/stable/tutorial/index.html
- Sebastian Raschka, Vahid Mirjalili. Python Machine Learning, 2nd Ed. Packt Publishing, 2017.

Description of the methods and technologies used in the project to solve the tasks set:

The following tools were used when executing the project:
- python programming language interpreter version 3.9;
- jupyterlab development environment version 4.0.0a16;
- scikit-learn library version 1.0.1;
- matplotlib library version 3.5.0;
- pandas library version 1.3.4.

