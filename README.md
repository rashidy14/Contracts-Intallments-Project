# Contracts-Intallments-Project
 
This is an Advanced PLSQL project, aims to on adding any new contract (id, start date, end date, total fees, deposit fees, payment type) in contracts table, installments number required for this contract is calculated and added in Contracts table, then the contract installation details(installment id ,contract id, installment amount , installment required dates) are calculated and automatically inserted in Installments table.

The project based on at first there's some clients who have contracts. Once we assign a contract to a client 
the triggers fires and do the following: 
* calculating the installments number based on the contract type, the start and the end date
* fill the installment paid table with rows equal to the installment number 
* update the notes column in clients tables 
 
 note : each table has a seq/trigger pair for the id column.

this code also handels the case when the client want to change the contract type or the contract duration. it calcultes the paid amounts to be considered in case of 
changing either the contract type or the duration.

### video illusrationg and testing the code : and testing the code:
https://drive.google.com/file/d/1mEBNo2LtW9spNNHnrCV8o2QaVAK33Pfn/view?usp=sharing

