# Electricity_Billing_System
This is a GUI System made using Java Swing . It has Database connectivity and uses JDBC to connect to MySQL.

This is a GUI made using Java Swing. It lets User perform multiple operations like:-

1- User can Create his Personal login for security purposes.

2- User can Add customers and Calculate their Electricity Bill.

3- User can Pay Electricity Bills.

4- User can Generate Bill.

Database for this Electricity Billing System contains 4 Tables

->Login Table (UserName,Password)

->Bill Table(MeterNumber,Units,Month,Amount)

->Emp Table(Name, MeterNumber, Address, State, City, Email, Phone)

->Tax Table(MeterLocation,MeterType,PhaseCode,BillType,Days,MeterRent,MCB_Rent,ServiceRent,GST)

Java communicates with MySQL tables using JDBC which stands for Java Database Connectivity.
