# MasterProject2021
Cybercrime cases currently involve demanding payment after infecting a victimized
organization’s computers with ransomware or impairing it is operations through a
distributed denial-of-service attack which significantly impacts the confidentiality, integrity and availability of data. Recent researchers show that hybridizing techniques
can detect malware or benign effectively. Our research provides an experimental
study on hybridizing machine learning and signature-based techniques to detect malware based on the PE header information. We used a dataset of 3787 benign and
11348 malware samples of portable executable files. We experimented with Anaconda,
Jupyter notebook, feature extraction, feature selection module in python was used.
The dataset was sliced randomly into training 80% and testing 20% sets. Different
classifiers which include Random Forest, Gradient Boosting and Ada boost were used
to training and test the data. The models evaluated using the evaluation metrics.
Results showed overall achieved accuracy is high for the cleaned dataset ranged from
99.70% to 99.77%, for the uncleaned dataset range from 93.83% to 96.83%. The
VirusTotal file report API had a high Average detection rate for unclean dataset
ranging from 0.00% to 12.57% and a low average detection rate of 0.00% on a cleaned
dataset. Random Forest emerged as the best classifier for both cleaned and uncleaned
dataset with an average detection rate for static analysis of 0.00% respectively
# requirements
You will need to request an API Key from VirusTotal.
install the requirements.txt
