## Online Payment Fraud Detection Model
### What is the problem?

Rapid digitisation of money has brought in a global shift towards online payment fuelled by the growth of mobile network and handphone ownership. Fintech businesses have thrived on this wave of digital money. From digital banks and payment processors to insurers, lenders and wealth managers, fintech firms are leveraging data and leading-edge technology to deliver more with less. A whopping two-thirds of people worldwide use digital modes to receive or make a payment (transactions). Keeping pace with the growth of digitisation, the cyber threats are not far behind. Billions of dollars of loss is caused by fraudulent credit card transactions every year. 
Fintech companies have the responsibility to implement robust anti money laundering and know your customer compliance processes. At the same time, they are driven by business needs to not compromise the quick, seamless customer experiences.

### What types of payment fraud are there?
There are multiple types of payment fraud:

![alt text](https://github.com/AmanRiar7/SLackathon-Online-Payment-Fraud-Detection--Team-Divas/blob/main/types_of_payment_frauds.png)
 
(https://seon.io/resources/building-a-stronger-payment-fraud-prevention-framework-for-your-business/)

With increase in use of credit cards, credit card fraud has become most common with millions of people falling victim to credit card fraud every year. There were 389,845 cases of credit card fraud reported in 2021 in the U.S.  
It is very crucial to identify fraudulent transactions so that credit card fraud can be curtailed. Fraud detection is the collection of processes and techniques that identify potentially fraudulent activities. Fraud detection is very important to identify, monitor, detect and prevent fraud. 

### How can technology help?

Security checks can be implemented by fintech companies at different stages of a transaction to detect and weed out fraudulent cases. Machine learning algorithms can be very fast and effective in identifying suspicious patterns and behaviour in the payment transactions. 

### The idea

In general, for fraud detection, machine learning algorithms are trained on historical data to suggest rules for flagging suspicious transactions. These are used by fintech companies to block or allow future transactions based on their assessment of the risk.

We will use a 3-step strategy to detect suspicious transactions:

Step 1: It is a fact that transaction data is unbalanced with fraudulent transactions forming a small percentage of the whole. We will first try techniques to balance out the data by boosting the minority class. 

Step 2:Following the logic that these fraudulent transactions must belong to a loosely cohesive set related in some manner like source,merchant, geography, time, type, methodology etc., it is important to detect this group that defines fraudulent transactions in a data set. Hence we will use clustering techniques to cluster the data into cohesive groups.

Step 3: Classification algorithms will then be used on the clustered dataset to classify the transactions as fraudulent or legitimate.

This 3-step approach should improve the efficiency and speed of the fraud detection model.

### Data Set

We will be using the dataset titled 'creditcard.csv' downloaded from (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### Architecture Diagram

![alt text](https://github.com/AmanRiar7/SLackathon-Online-Payment-Fraud-Detection--Team-Divas/blob/main/architecture_diagram.png)
![alt text](https://github.com/AmanRiar7/SLackathon-Online-Payment-Fraud-Detection--Team-Divas/blob/main/model_presentation.mp4)
