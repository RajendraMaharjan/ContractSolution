ContractSolution
================

YI solution

Select * from Contracts c
Inner join on Awards a 
Where c.ContractName=a.ContractName

Select sun(Amount) 
As Total_Amount
From Contracts
Where status="Closed"
