# Ames_prediction
Pharmaceutical companies are always looking for more efficient ways to assess drug toxicity, as traditional in vitro testing can be expensive and take up to 48 hours. In contrast, in silico prediction models provide quick and inexpensive alternatives. However, the adoption of such models is hindered by their less-than-perfect accuracy, which can be attributed to the complexity of toxic processes and the diverse range of molecules involved in drug development. 

This project specifically focuses on mutagenicity, which refers to the ability to cause DNA mutations - a key toxic risk. The Ames test, a standard in vitro assay for mutagenicity, is the primary focus of this exercise. The goal is to create a predictive mutagenicity model using available data on compounds that have been subjected to the Ames test. 

In the data, the 'ames' features equal to 0 mean non-toxic, while 1 mean toxic.

From 4 datasets, there are initially 1558 features, including both fingerprint-based and descriptor-based features. Three models were investigated, including KNN, SVM, and RF Classification. The accuracy was the main evaluation score. Also, the PCA was introduced to reduce the multicollinearity in the raw dataset, which had more than 1000 features. 

**Conclusion**:

