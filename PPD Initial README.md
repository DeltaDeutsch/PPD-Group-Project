# PPD-Group-Project
Proposal: https://docs.google.com/document/d/1AQNy7EDIod-bVpC3YMotVV52N4gtP-yYLFkwN3FchC8/edit\n

Data Source: "http://publicplansdata.org/api/"\n
Sample Direct API query: http://publicplansdata.org/api/?q=QVariables&variables=fy,PlanName,PercentReqContPaid,InvestmentReturn_5yr,ActFundedRatio_GASB&filterfystart=2000&filterfyend=2019&format=json\n

Variables of Interest:\n
 
Funded Ratio\n
dataset: pensiongasbschedules\n
variable name: ActFundedRatio_GASB\n
DESCRIPTION\n
Funded ratio measured under traditional GASB 25 standards. The (GASB 25) funded ratio is equal the the actuarial assets divided by the actuarial liability.\n

Total Membership, Plan ID, Plan Name\n
dataset: pensionmembership\n
variable name: totmembership, ppd_id, PlanName\n
DESCRIPTION: 
