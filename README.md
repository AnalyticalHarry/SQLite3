**Hemant Thapa**  
- [LinkedIn](https://www.linkedin.com/in/thapahemant/)  
- Email: [hemantthapa1998@gmail.com](mailto:hemantthapa1998@gmail.com)  


SQLite is a lightweight, serverless, and self-contained relational database engine. It is embedded within many applications, making it a popular choice for mobile and desktop applications. SQLite databases are simple files that can be easily shared or moved across different platforms. It supports a subset of SQL features and provides a practical solution for scenarios where a full-fledged database server might be excessive.

Installation 

```bash
pip install sqlite3
```

Student Database Managment System
https://github.com/AnalyticalHarry/SQLite3-LassoRegressionUsingFinanceData/blob/main/1%20Student%20Database.ipynb

Converting CSV File to Database Table
https://github.com/AnalyticalHarry/SQLite3-LassoRegressionUsingFinanceData/blob/main/2%20Customer%20Database%20-%20Converting%20csv%20file%20to%20database.ipynb

Converting Database to CSV & Data Visualisation
https://github.com/AnalyticalHarry/SQLite3-LassoRegressionUsingFinanceData/blob/main/3%20Converting%20Database%20to%20CSV%20%26%20Data%20Visualisation.ipynb

Employee Data Collection
https://github.com/AnalyticalHarry/SQLite3-LassoRegressionUsingFinanceData/blob/main/4%20Employee%20Data%20Collection.ipynb

Stock DataBase
https://github.com/AnalyticalHarry/SQLite3-LassoRegressionUsingFinanceData/blob/main/5%20Stock%20DataBase%20SQL.ipynb

LASSO REGRESSION : SQL DATABASE (MSFT & AAPL)
https://github.com/AnalyticalHarry/SQLite3-LassoRegressionUsingFinanceData/blob/main/6%20Lasso%20Regression%20SQL%20Database.ipynb

### Advantages:

- Serverless and Self-contained: SQLite is a serverless and self-contained database engine. It doesn't require a separate server process to operate. The entire database is contained in a single file, making it easy to manage.

- Zero Configuration: There is no complex setup or administration required. You can start using SQLite by simply connecting to a database file.

- Lightweight: SQLite is designed to be lightweight, both in terms of its memory footprint and its storage requirements. This makes it suitable for embedded systems and devices with limited resources.

- Cross-Platform: SQLite is cross-platform and works on various operating systems, including Windows, Linux, and macOS.

- Transactional Database: SQLite supports ACID properties (Atomicity, Consistency, Isolation, Durability), making it suitable for applications requiring transactional support.

- Widely Used: SQLite is extensively used in embedded systems, mobile applications (both Android and iOS), and desktop applications.

### Disadvantages:

- Concurrent Write Performance: SQLite might not perform as well as some other database systems in scenarios with heavy concurrent write operations. Its write performance can be affected when multiple users are trying to write simultaneously.

- Limited Concurrency: While SQLite supports multiple concurrent reads, it has some limitations in terms of concurrent write operations.

- Not Suitable for Large-Scale Systems: SQLite is not ideal for large-scale systems with a high volume of concurrent transactions and complex queries. In such cases, a client-server database like MySQL or PostgreSQL might be more appropriate.

- No User Management: SQLite lacks advanced user management and access control features compared to larger database systems.

- Stored Procedures: SQLite does not support stored procedures, which can limit its use in certain scenarios that require complex database logic.

- Single User Write: SQLite is designed for single-user write scenarios. If you need multiple users to write to the database simultaneously, you might need to consider other database solutions.
