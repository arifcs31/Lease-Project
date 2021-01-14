Lease Payment Calculation

**Introduction**

I have created a new asp.net MVC application. There are basically two views in which I have implemented this logic to show data to the end user. 
 You can run the application because it is very simple application.
 
**Database**

For creating database, I have created two tables in SQL Server (Lease and LeasePayments). So, you can just restore the back up and change the connection string accordingly like username and password.
I have also generated the script as well.

If backup not restored due to some SQL version issue, then I have attached table design view. It is very simple.

**Import (001 user story)**

When you select csv file and click on import button then if file passes the validation it will be saved in database. I have also implemented one logic to store lease in lease table and lease payment that follow the formula will be saved in lease payments table. 

**Export (002 user story && 003 user story)**

When you click on export button then you can view all stored leases on page.
For Export => When clicking on export link against each lease then according to start and end date I am getting Lease Payments and creating the CSV file that will be downloaded at that time.

**Note**
I have spent 15 hours to complete this assignment. I know there might be chance some business logic issue in user story 003 but I have completed it according to my understanding.

I hope it will help you to analyze my technical and business skills. I am excited to listen yours positive response. Thank you

