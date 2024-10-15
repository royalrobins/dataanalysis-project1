<h1>Data Analysis Personal Project (Microsoft's AdventureWorks Dataset)</h1>

In this project I will find the relationship of the standard cost and list price of products found in a sample dataset provided by Microsoft which is AdventureWorks. This project serves as a way to test my knowledge on ETL practices as well as experience working with databases.

<h1>Prompt: Using the Microsoft AdventureWorks sample dataset, write a SQL query to find the relationship between a product's standard cost of production and its list price based on product model. Once the data is gathered, import it into Excel to find the price increase/decrease in percentage format from standard cost of production to list price.</h1>

To start this project, I needed to find a sample dataset and database to store the sample dataset in. I opted to use Microsoft Azure services to further my education with homelabs, including this project. I created a SQL Server in Azure so that the SQL database can be successfully stored. 

<img width="647" alt="Screenshot 2024-10-14 191408" src="https://github.com/user-attachments/assets/0a86c63f-78f4-49ad-ac23-82ae13e572c8">

During the creation process of the SQL database, I opted to import Microsoft's AdventureWorks dataset. 

<img width="779" alt="Screenshot 2024-10-14 191731" src="https://github.com/user-attachments/assets/21262594-4ae8-4272-9fae-db1cb18cb94b">

Once everything completed its deployment in Azure, I then downloaded Microsoft's SQL Server Management Studio (SSMS) to use as an on-prem SQL Management software. Once it was downloaded, I connected it to the SQL Server I created in Azure by copy and pasting the server link and admin credentials. Now that everything was successfully authenticated, I was ready to write queries in the database that I created in Azure.

![image](https://github.com/user-attachments/assets/333f64f6-ed8b-456f-9be5-938c160f6c02)

Now that I connected SSMS to the SQL Server I created in Azure, I was ready to begin writing queries.

