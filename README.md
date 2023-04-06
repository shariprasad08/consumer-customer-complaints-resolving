# Consumer Complaints Resolution
For any organisation, resolving customer complaints is important.

Do not use date columns as is; you can use them to create other features.
handle columns Issue & Consumer Complaint Narrative, creatively. See if you can create some good feature from this column containing text data. [tfidf ?]
It doesnt make sense to use Consumer ID as predictor.
Break the train data into two parts and use one to build model and test its performance on the other.
If you are creating any new features on your training data or modifying features in the train; you will have to do that for test data also. This is needed so that the model which was built using the training data can be used for the test data to make predictions.

Dataset description
Customers faced some issues and tried to report their problems to customer care.
Dispute: This is our target variable based on train data we have two groups, one with a dispute with the bank and another don’t have any issue with the bank.
Date received: The day complaint was received.
Product: different products offered by the bank (credit cards, debit cards, different types of transaction methods, accounts, locker services, and money-related)
Sub-product: loan, insurance, other mortgage options
Issue: Complaint of customers
Company public response: Company’s response to consumer complaint
Company: Company name
State: State where the customer lives 
ZIP code: Where the customer lives
Submitted via: Register complaints via different platforms 
Date sent to company: The day complaint was registered
Timely response?: Yes/noConsumer
disputed?: yes/no (target variable)
Complaint ID: unique to each consumer


Prediction
RandomForest Classifier gives us the most accurate result hence RandomForest Classifier will be the final model used for prediction

Conclusion
In conclusion, the goal of this project was to create a machine learning model that could forecast whether or not a customer complaint will be resolved. The model was tested using accuracy scores and classifier comparison plots after being trained on a preprocessed dataset of customer complaints. The final prediction was based on the model that performed the best.For businesses that deal with consumer complaints, the project's findings can be helpful since they can show them which concerns are most likely to be settled and which are more likely to turn into disputes. The resource allocation process can then be improved and the whole complaint resolution procedure can be enhanced using this information.
