# PPD-Group-Project
Proposal: https://docs.google.com/document/d/1AQNy7EDIod-bVpC3YMotVV52N4gtP-yYLFkwN3FchC8/edit

Data Source: "http://publicplansdata.org/api/"

Sample Direct API query: http://publicplansdata.org/api/?q=QVariables&variables=fy,PlanName,PercentReqContPaid,InvestmentReturn_5yr,ActFundedRatio_GASB&filterfystart=2000&filterfyend=2019&format=json

Variables of Interest:
 
Funded Ratio
dataset: pensiongasbschedules
variable name: ActFundedRatio_GASB
DESCRIPTION
Funded ratio measured under traditional GASB 25 standards. The (GASB 25) funded ratio is equal the the actuarial assets divided by the actuarial liability.

Total Membership, Plan ID, Plan Name
dataset: pensionmembership
variable name: totmembership, ppd_id, PlanName
DESCRIPTION: 
