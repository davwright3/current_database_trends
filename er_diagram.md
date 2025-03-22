
# This file is for the ER diagram for the project.

## Online banking database system:
 The online banking database will require information to be kept on the customers in the database. Some attributes to be included will be a Customer ID, Customer SSN, name, address, and phone number. It will also contain information on the accounts in the system. The attributes included in this will be the account number, the customer ID, account type, and balance. The database will also include data on investment accounts which will include investment ID, customer ID, investment type (stocks, bonds, mutual funds), investment amount, current value. After that the database will contain information on loans which will contain a Loan ID, customer ID, loan type, loan amount, interest rate, current balance. Lastly the database will contain information on transactions which will contain Transaction ID, account number, transaction type (deposit, withdrawal, transfer), amount, transaction date.

 ## ER Diagram
 ```mermaid
erDiagram

Customer{
 CustSSN integer PK
 CustID integer PK    
}


```
