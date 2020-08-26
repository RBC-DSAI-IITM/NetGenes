**README file for EssGeneFromNet feature matrices**

--------------------

Training data:
The training data zip file contains two text files - NegativeTrainingSet.csv and PositiveTrainingSet.csv. These files correspond to the negative feature vectors and positive feature vectors used in training the model. The machine learning algorithm used is Random Forest Classifier (sklearn-0.23.1 implementation).

Feature matrices given here are extracted using ReFex method. The variant used in building model is '283 network'. This variant was selected to ensure features extracted are purely network-oriented.

--------------------

Feature matrices - individual species:
Feature matrices for each organism hosted in our database EssGeneFromNet is provided in the Downloads page. First column in the feature matrix corresponds to STRING ID of the gene, followed by 283 features used in the machine learning model. First 267 values in each feature vector corresponds to ReFex features and the rest are centrality measures calculated for the corresponding gene node. The names of features used are given in features_list.txt.

--------------------

To learn more about the features and the variants, read our original research paper: Azhagesan, K., Ravindran, B., & Raman, K. (2018). Network-based features enable prediction of essential genes across diverse organisms. PLOS ONE, 13(12), e0208722. https://doi.org/10.1371/journal.pone.0208722