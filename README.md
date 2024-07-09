# Insurance-Fraud-Detection-Model-


Introduction
This repository contains a Python-based fraud detection model designed to identify fraudulent insurance claims. The model utilizes a dataset with various features that describe the context of insurance claims, including temporal information, personal details of the policyholder, and characteristics of the policy and vehicle involved.

Dataset Description:  The dataset used for training and evaluating the fraud detection model includes the following features:
1. Month: The month in which the accident occurred.
2. WeekOfMonth: The week of the month in which the accident occurred.
3. DayOfWeek: The day of the week on which the accident occurred.
4. Make: The make of the vehicle involved in the accident.
5. AccidentArea: The area where the accident occurred.
6. DayOfWeekClaimed: The day of the week on which the claim was filed.
7. MonthClaimed: The month in which the claim was filed.
8. WeekOfMonthClaimed: The week of the month in which the claim was filed.
9. Sex: The gender of the policyholder.
10. MaritalStatus: The marital status of the policyholder.
11. Age: The age of the policyholder.
12. Fault: Indicates whether the policyholder was at fault in the accident.
13. PolicyType: The type of insurance policy.
14. VehicleCategory: The category of the vehicle.
15. VehiclePrice: The price of the vehicle.
16. FraudFound_P: A binary indicator (0 or 1) representing whether fraud was found in the claim.
17. PolicyNumber: The policy number associated with the claim.
18. RepNumber: The number of the representative handling the claim.
19. Deductible: The deductible amount on the policy.
20. DriverRating: The rating of the driver.
21. Days_Policy_Accident: The number of days between the policy start date and the accident date.
22. Days_Policy_Claim: The number of days between the policy start date and the claim date.
23. PastNumberOfClaims: The number of past claims made by the policyholder.
24. AgeOfVehicle: The age of the vehicle at the time of the accident.
25. AgeOfPolicyHolder: The age of the policyholder at the time of the accident.
26. PoliceReportFiled: A binary indicator (0 or 1) indicating whether a police report was filed.
27. WitnessPresent: A binary indicator (0 or 1) indicating whether a witness was present at the accident.
28. AgentType: The type of agent who sold the policy.
29. NumberOfSuppliments: The number of supplements to the claim.
30. AddressChange_Claim: A binary indicator (0 or 1) indicating whether the policyholder changed their address after the claim.
31. NumberOfCars: The number of cars insured under the policy.
32. Year: The year in which the accident occurred.
33. BasePolicy: The base policy amount.

Model Overview
The fraud detection model is built using machine learning algorithms that can handle classification tasks. The model is trained to predict the FraudFound_P column, which is the target variable indicating whether a claim is fraudulent.

Features Used
The model utilizes a subset of the features listed above. Feature selection is performed to identify the most relevant and predictive features for detecting fraud.

Model Training
The model is trained using a supervised learning approach. The training process involves splitting the dataset into training and testing sets, preprocessing the data, and applying machine learning algorithms to learn patterns that distinguish fraudulent claims from legitimate ones.

Evaluation Metrics
The performance of the model is evaluated using metrics such as accuracy, precision, recall, F1 score, and the area under the ROC curve (AUC). These metrics help in assessing the model's ability to correctly identify fraudulent claims.

Usage
To use the fraud detection model, follow these steps:

Clone this repository to your local machine.

Install the required Python packages by running pip install -r requirements.txt.

Prepare your dataset in the same format as the training data.

Run the model training and evaluation scripts provided in the repository.

Use the trained model to predict fraudulent claims in new data.

Contributing
Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the contributors who helped with the development and testing of the model.
Acknowledgment to the dataset providers (if applicable).
