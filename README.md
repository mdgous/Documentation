Documentation
=============

still java class and parameters,functions needs to be added



  
SQL Engine Database Documentation (UNFSQLteam2) 
1.	UNFSQLteam2
2.	Data Model Diagrams
				Documentation
				Documentation generated on 11/20/12 at 2:30 P.M
				
				Database Objects
TYPE	COUNT
TABLES	4
FUNCTIONS	
ALL PARAMETERS	
ALL COLUMNS	16
				




				Database Properties
NAME	VALUE
NAME	UNFSQLteam2
SERVER	LOCALHOST
SERVER VERSION	1.0

				
				





1. UNFSQLteam2
	1.1 Tables
		1.1.1 Table Supplier
			1.1.1.1Table Properties  	
					Name			Value
Name	Supplier
Created	11/20/12  2:30 PM
Row Count	3
Size of Data	10kb
Index	0
Average Row Length	100b
Engine	UNFSQLteam2
Row Format	Compact
Version	1.0
Auto Increment	Yes
			

	
	  		1.1.1.2  Columns

Column	Data Type            	Length	PK	FK	UQ	Privileges	Comments
SNO	NUMBER	3	Yes		Yes	Select, Insert, Update, Delete	
S Name	CHAR	15					
ADDRESS	CHAR	15					
CUSTNO	NUMBER	3			Yes		
				       







	1.1.2 Table Customer
		1.1.2.1 Table Properties  
					Name			Value
Name	Customer
Created	11/20/12  2:30 PM
Row Count	3
Size of Data	10kb
Index	
Average Row Length	100b
Engine	UNFSQLteam2
Row Format	Compact
Version	1.0
Auto Increment	Yes
			

	


	







				   1.1.2.2 Columns

Column	Data Type            	Length	PK	FK	UQ	Privileges	Comments
CUSTS NO	NUMBER	3	Yes		Yes	Select, Insert, Update, Delete	
CName	CHAR	15					
ADDRESS	CHAR	15					
SNO	NUMBER	3			Yes		





1.1.3 Table Order
			1.1.3.1 Table Properties  		
					Name			Value
Name	Order
Created	11/20/12  2:30 PM
Row Count	3
Size of Data	10kb
Index	0
Average Row Length	100b
Engine	UNFSQLteam2
Row Format	Compact
Version	1.0
Auto Increment	Yes
			
	









				  1.1.3.2 Columns

Column	Data Type            	Length	PK	FK	UQ	Privileges	Comments
Order NO	NUMBER	3	Yes		Yes	Select, Insert, Update, Delete	
O Status	CHAR	15					
DATE	DATE						
CUSTNO	NUMBER	3			Yes		









1.1.4 Table Product
			1.1.4.1 Table Properties  	
						Name			Value
Name	Product
Created	11/20/12  2:30 PM
Row Count	3
Size of Data	10kb
Index	0
Average Row Length	100b
Engine	UNFSQLteam2
Row Format	Compact
Version	1.0
Auto Increment	Yes
					



Column	Data Type            	Length	PK	FK	UQ	Privileges	Comments
PNO	NUMBER	3	Yes		Yes	Select, Insert, Update, Delete	
P NAME	CHAR	15	No				
QTY	NUMBER	3	No				
CUSTNO	NUMBER	3	No		Yes		
				
			1.1.4.2 Columns



			


	

All Table Columns
Parent	Column	Definition
SUPPLIER	SNO	NUMBER(3)
SUPPLIER	SNAME	CHAR(15)
SUPPLIER	ADDRESS	CHAR(15)
SUPPLIER	CUSTNO	NUMBER(3)
CUSTOMER	CUSTNO	NUMBER(3)
CUSTOMER	CNAME	CHAR(15)
CUSTOMER	ADDRESS	CHAR(15)
CUSTOMER	SNO	NUMBER(3)
PRODUCT	PNO	NUMBER(3)
PRODUCT	PNAME	CHAR(15)
PRODUCT	QTY	NUMBER(3)
PRODUCT	CUSTNO	NUMBER(3)
ORDER	ORDERNO	NUMBER(3)
ORDER	OSTATUS	CHAR(15)
ORDER	DATE	DATE
ORDER	CUSTNO	NUMBER(3)
				







   









Functions		Function Over 
Name	Created	Dependents 	Depends on	Comments
				
				
				
	

Procedures
					
					
					
			




All Procedure Parameters
			
Procedure	Type	Parameter 	Data Type	In/Out
				
				
				

3.	Data Model Diagrams
3.1 All Objects
3.2 All Tables
			Data Model Diagrams
Name	Description	Objects in Model
All Objects		
All Tables		4

					





3.1 All Objects
		












3.2 All Tables   										
Supplier
Sno         Number
SName    Char
Address   Char
CustNo   Number

Order
Orderno  Number
OStatus   Char
Date        Date
CustNo   Number

										
Product
Pno        Number
PName   Char
Qty         Number
Cust No  Number

			
Cust
Custno    Number
CName     Char
Address    Char
SNo        Number

	
	

