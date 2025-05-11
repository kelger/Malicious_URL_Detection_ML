# Malicious_URL_Detection_ML
Tools: Python, Scikit-learn, Pandas, Regex Built an ML model to classify URLs as malicious or benign using lexical features. Used vectorization and trained models like Random Forest and SVM, achieving 95%+ accuracy. Helped enhance threat detection and web security.

Brief Description

This project focuses on detecting malicious URLs using machine learning techniques. The dataset comprises URLs labeled as benign, phishing, defacement, or malware. Key features are extracted from these URLs, including URL length, presence of IP addresses, use of HTTPS, special character counts, and lexical features. Multiple classifiers such as Decision Trees, Random Forests, and others are trained and evaluated to accurately identify harmful links, aiming to enhance cybersecurity defenses against phishing and web-based attacks.

Workflow

1. Data Collection: The dataset containing URLs with labels is loaded for analysis.

2. Feature Extraction: Various features are extracted from each URL, including URL length, number of special characters, presence of IP addresses, and use of URL components like '@', '?', '-', etc.

3. Data Preprocessing: Data is cleaned, and features are prepared for model training.

4. Model Training: Different machine learning classifiers are trained on the features to predict whether a URL is malicious or benign.

5. Model Evaluation: Models are evaluated based on accuracy, precision, recall, and F1-score using cross-validation and test datasets.

6. Visualization: Graphs such as confusion matrices, feature importance plots, and ROC curves are generated to analyze model performance and feature significance.

Insights Generated

- URL length and the presence of IP addresses are strong indicators of malicious URLs.

- URLs containing special characters like '@', '?', '-', and '=' are more likely to be malicious.

- The Random Forest classifier achieved the highest accuracy (~XX%) among tested models.

- Feature importance analysis revealed that URL length, presence of IP, and use of specific special characters significantly influence the detection accuracy.

- Visualizations demonstrated the distribution of features across benign and malicious URLs, and ROC curves showed the models' discriminative power.

Graphs

- Feature Importance Plot: Shows the relative importance of each feature used in the best-performing classifier.

- Confusion Matrix: Visualizes the true vs. predicted labels for the classifiers.

- ROC Curve: Demonstrates the trade-off between true positive rate and false positive rate for the classifiers.

- Distribution Graphs: Histograms comparing feature distributions (e.g., URL length, special characters) between benign and malicious URLs.

Conclusion

This study illustrates that machine learning models, particularly Random Forest, can effectively identify malicious URLs, leveraging features like URL length, presence of IP addresses, and special characters. The implementation of such automated detection mechanisms can substantially improve cybersecurity measures by proactively flagging potentially dangerous links in real-time.
