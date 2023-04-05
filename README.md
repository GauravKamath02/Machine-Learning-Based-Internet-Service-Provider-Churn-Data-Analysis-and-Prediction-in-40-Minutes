# Machine-Learning-Based-Internet-Service-Provider-Churn-Data-Analysis-and-Prediction-in-40-Minutes

Code is a result of the quick 40 minutes implementation round, part of the CodeCrunch challenge held at Dayananda Sagar University, March 2023. The challenge gauged our ability to handle and explain ML algorithms in a limited timeframe. Model takes in customer churn data and can also predict outcomes based on custom data and attribute entry. Project ranked 3rd in the 25 team contest.

- Dataset used:ISP Network Churn [CCO OpenSource]
- Algorithm used: Naive Bayes
- Accuracy: 81% [Can be improved by data handling, not looked into much due to time constraints]
- Techniques seen: -> Missing value handling
                   -> Corelation checking
                   -> Feature Scaling
                   -> Performance evaluation
                   -> Custom user input snippet

Do go through our presentation attached for better understanding.



## MetaData
| ATTRIBUTE | DETAIL |
| ------ | ------ |
| id |unique subscriber id |
| is_tv_subscriber | customer has a tv subscription ? |
| is_movie_package_subscriber | customer has a  movie package subscription ? |
| subscription_age | no of years customer has been using our services |
| bill_avg | last 3 months bill avg|
| reamining_contract |how many year remaining for customer contract. if null; customer hasnt have a contract. the customer who has a contract time have to use their service until contract end. if they canceled their service before contract time end they pay a penalty fare. |
| service_failure_count | customer call count to call center for service failure for last 3 months|
| download_avg |last 3 months internet usage (GB) |
| upload_avg | last 3 months upload average (GB) |
| download_over_limit | most of customer has a download limit. if they reach this limit they have to pay for this. this column contain "limit over count" for last 9 months |
| churn | target column.  1 if customer canceled his service |
