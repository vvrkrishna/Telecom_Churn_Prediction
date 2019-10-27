# Churn prediction for Telecom
## Problem Description
To predict the telecom customers who are likely to exit the contract and also to generate patterns of Churn and non-churn to assist the management to take appropriate decisions to limit churn.

# Data
The datasets are provided as cited below for the analysis:

1. Demographics Data: “Train_Demographics.csv” & “Test_Demographics.csv” These files consist of the demographic data of each customer, like HouseholdID, Country, State, Education, Gender etc.
2. Account Information: “Train_AccountInfo.csv” & “Test_AccountInfo.csv” These files consist of the customer account information with the telecom company, like CustomerID, DOE, Contract Type, Paymentmethod etc.
3. Data of ServicesOptedFor: “Train_ServicesOptedFor.csv” & “Test_ServicesOptedFor.csv” These files consist of the details about the services the customers signed for
4. Churn Data: “Train.csv” & “Test.csv” This “Train.csv” table contains the Customer churn details - CustomerID, Churn. This “Test.csv” contains only CustomerID (Not target attribute, which is to be predicted)
    5. Attributes Details: “AttributeInformation.docx” This has the details of attributes for the datasets cited above (1 to 4)
    
    
# Main Tasks
1.	Exploratory data analysis using visualizations in Jupyter notebook format.
2.	Built a model that predicts whether a customer churns or not from the company.


## Information about attributes:

Demographics Data : 
	•	HouseholdID : Each Household id
	
	• 	Country : Country. ( For this attribute, missing values   are denoted as “?”)
	
	•	State : State ( For this attribute, missing values are denoted as “?”)
	
	•	Retired : Whether retired
	
	•	HasPartner : Demographic information - whether the customer has partner ( 1-Yes; 2-No)
	
	•	HasDependents : Demographic information - whether the customer has dependents ( 1-Yes; 2-No)
	
	•	Education : Education qualification
	
	•	Gender : Demographic information – gender


Account Information :

	•	CustomerID : CustomerID
	
 	• 	BaseCharges : Customer account information (Charges for Base plan)
	
	•	DOC : Date of data collection
	
	•	TotalCharges : Customer account information( For this attribute,missing values are denoted as “MISSINGVAL” also)
	
	•	DOE : Date of entry as customer
	
	•	ElectronicBilling : Customer account information - whether electronic billing
	
	•	ContractType : Contract type ( For this attribute, missing values are denoted as “NA”)
	
	•	PaymentMethod : payment method

Data of ServicedOptedFor : 

	•	CustomerID : CustomerID
	
	•	TypeOfService : Service signed for    
	
	•	ServiceDetails : did the customer opted for that particular service


Churn Data : 	

	•	CustomerID : Customer ID
	
	•	Churn : Whether the customer churns  (Target)
