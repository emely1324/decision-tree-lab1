# Decision Tree Lab 1  

## 📄 Overview  
This repository contains the **Lab 1 Report** (`LAB 1 report_merged.pdf`), which documents the implementation and analysis of **decision tree classification** on the Iris dataset. The lab explores entropy-based splits, visualizations of decision trees, and classification outcomes for three Iris flower species.  

## 📂 Contents  
- `LAB 1 report_merged.pdf` – Full lab report with results, visualizations, and analysis  
- Decision tree diagrams with entropy and class distribution  
- Classification results for **Setosa, Versicolor, and Virginica**  

## 🧑‍💻 Methods  
- **Dataset**: Iris dataset (150 samples, 3 classes)  
- **Algorithm**: Decision Tree Classifier (`criterion="entropy"`)  
- **Metrics**: Entropy, information gain, classification accuracy  
- **Tools**: Likely implemented with Python, `scikit-learn`, `pandas`, `matplotlib`  

## 🚀 How to Replicate  
1. Load the Iris dataset with:  
   ```python
   from sklearn.datasets import load_iris
   iris = load_iris()
   
2. Train a decision tree
   ```python
   from sklearn.tree import DecisionTreeClassifier
   clf = DecisionTreeClassifier(criterion="entropy")
   clf.fit(iris.data, iris.target)

3. Visualize the tree
   ```python
   from sklearn import tree
   tree.plot_tree(clf, filled=True, feature_names=iris.feature_names, class_names=iris.target_names)




📌 Notes
This repository is for educational purposes as part of Lab 1.
Useful as a reference for machine learning coursework or decision tree fundamentals.
Report includes step-by-step entropy calculations and classification breakdowns.
