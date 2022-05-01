## Log File Processing and Anomaly Detection on HDFS Log Dataset

#### Data 586: Advanced Machine Learning: Final Report
Harpreet Kaur Guglani & Kristy Phipps

The challenge of processing log files for anomaly detection was undertaken as part of a final paper and project. This project was completed during the Master of Data Science (MDS) degree at UBC and was completed over a four week period concurrent with our coursework for Data 586 - Advanced Machine Learning. 

The data for this project was sourced from [Loghub](https://github.com/logpai/loghub) which maintains a collection of system logs freely accessible for research purposes. Additional resources were sourced from the [LogParser](https://github.com/logpai/logparser) and [Loglizer](https://github.com/logpai/loglizer) libraries. 

Understanding that real-time detection of anomalies is one of the primary goals within industry, efforts were focused on speed of data processing and predictive accuracy. To support this, a machine learning pipeline was built to process the data and extract key features. For this, the Drain parser from the [Loglizer](https://github.com/logpai/loglizer) library was selected based on its ability to process streaming or static data quickly and accurately. These results were then fed into a machine learning model. The Random Forests model was chosen for its high predictive accuracy. Ultimately, this combination of tools worked incredibly well together, and resulted in a 99.98% prediction accuracy on the 15% test set withheld from the original data. 

This was an interesting project to undertake as part of the MDS program. We are hopeful this work will highlight both how easy to implement and how powerful the open-source toolkits can be for processing unstructured log data into meaningful insights. 
