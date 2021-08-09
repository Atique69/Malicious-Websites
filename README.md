# Malicious-Websites

## Kaggle Competition: https://www.kaggle.com/xwolf12/malicious-and-benign-websites

The project consisted to evaluate different classification models to predict malicious and benign websites, based on application layer and network characteristics. The data were obtained by using different verified sources of benign and malicious URL's, in a low interactive client honeypot to isolate network traffic. We used additional tools to get other information, such as, server country with Whois.

This is the first version and we have some initial results from applying machine learning classifiers in a bachelor thesis. Further details on the data process making and the data description can be found in the article below.

### Dataset
This is an important topic and one of the most difficult thing to process, according to other articles and another open resource, we used three black list:

* machinelearning.inginf.units.it/data-andtools/hidden-fraudulent-urls-dataset
* malwaredomainlist.com
* zeuztacker.abuse.ch

From them we got around 185181 URLs, we supposed that they were malicious according to their information, we recommend in a next research step to verity them though another security tool, such as, VirusTotal.
