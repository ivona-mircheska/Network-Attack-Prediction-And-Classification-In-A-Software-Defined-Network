
The project includes two Jupyter notebooks: one for Binary Classification and another for Multi-class Classification.

The Binary Classification notebook utilizes machine learning models to determine whether an attack is occurring on the network. The Multi-class Classification notebook, on the other hand, is designed to identify eight different types of attacks within a software-defined network.

The dataset used in this project is the InSDN database, which features attack data from an SDN network. This database includes 83 attributes, 343,889 instances, and 8 distinct attack categories: Normal (68,424 instances), DoS (53,616 instances), DDoS (121,942 instances), Probe (98,129 instances), Botnet (164 instances), U2R (17 instances), Web Attack (192 instances), and BFA (1,405 instances).

The data is split into 80% for training (275,111 instances) and 20% for testing (68,778 instances). Additionally, Stratified five-fold cross-validation (StratifiedKFold) is implemented on the training data to enhance the models' ability to generalize effectively.

For developing the machine learning models, I employed the PyCaret library in Python. I built several models, including XGBoost, Random Forest, Decision Tree, K-Nearest Neighbors (KNN), SVM with a linear kernel, Naive Bayes, and Logistic Regression.
