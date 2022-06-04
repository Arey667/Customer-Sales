# Customer-Sales

Customer satisfaction is based on 2 data points: 1) Timely deliveries, and 2) Product quality.  The infrastructure needed to deliver a product on time is a complex system requiring the management of a horizontally integrated end-to-end infrastructure. This end-to-end process involving monitoring products from raw material to finished product, and precise logistics to deliver based on the customer’s needs.


## Features selected were 16 from company data seen here.  Data was a mix of numerical and string data :

- Fiscal Quarter	
- Engineer
- Fiscal week	
- Sales Order #
- Machine #	
- Plant
- Built Type	
- Customer Date: Planned
- Location	
- Customer Date: Actual
- Customer Name	
- Ship Planned
- Account	
- Ship Actual
- Manager	
- Ship to Region
- Product type	
- Platform

## Performing 6 Classification models shows there is a mix of correlation results.  Initial results show most models performed in the 80-90% range.  Recall and F1 scores were mixed. 

## Conclusion
Machine learning classification modeling shows there are benefits in using different models to obtain the best predictive model.  Although not the best results, the best performer was Logistic Regression CV with 88.49% Accuracy, 61.64% Recall, and 17% F1 scores. the AUC is 54%
Switching to a neural network Keras model, the results were more predictable with 85% accuracy and 0.136 loss.
Certain regions, product type, and customers have higher late orders.  This insight can help in deep diving in what specific circumstances causes these specific features to reflect this pattern.  
Customer orders are critical to business’s lifeline.  Having an accurate forecast is complex and crucial.  Many influential factors which can fall outside of a company’s control.  It is important to consider these factors which may occasionally impact orders.  Fore example, geo-political events, pandemics, war, climate events are all unpredictable features which require outside actions to address.  

 
