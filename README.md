# Research-articles-mentioned-in-news-articles

The main idea of this project is to predict wether a given research article can get published in a news article by considering the popularity of research article on social media.

--Data Collection:
          Data is collected from Altmetrics (https://www.altmetric.com/) where data is in the form of json files. Each json file will               have the information like the details about the article and social media discussion about that article.
           
--Data Cleaning:
          Here the major concern of data munging was that data was in string format. Data cleaning is done using python and data is                 finally transfered into CSV format.
            
 --Building the classifier: 
 
        finaldataclassifier: This file contains the python code where the classifiers are created using the data collected and classifier         is validated using the metrics. ROC curve is also drawn to visualize the performance of the classifier.

        results.txt: This file contains the result(metrics) of the classifiers that is created on the data.
        
        
