
### Project TiTle:
 Uncovering Anomalies: A Deep Dive into Login Attempts and Employee Data

### Project Introduction :
 To prevent potential security breaches, we carefully examined the company's login attempts and employee records. Our goal was to uncover unusual patterns that might signal unauthorized access or compromised 
 accounts.
 To do this, we used SQL commands to extract and analyze the necessary information.

### Modeling and Evaluation
The core of our analysis involved data exploration and pattern recognition within the `log_in_attempts` and `employees` tables. Key SQL queries were designed to:
*  Retrieve after hours failed login attempts .
* Retrieve login attempts on specific dates.
* Retrieve login attempts outside the country.
* Retrieve employees in Marketing , Sales AND Finance Departments .
*  Retrieving  all employees  that are not in  IT(Information technology).

Evaluation metrics included:
Based on the SQL queries and assumptions, here are some potential evaluation metrics:

`General Metrics`
# Data Quality:
Percentage of missing values in each column.
Consistency checks for data types and formats (e.g., date formats).
Duplicate records in both tables.
# Data Volume:
Number of records in each table.
Growth rate of data over time.

`Specific Query Metrics`
# Retrieve after hours failed login attempts:
Number of failed login attempts outside regular working hours.
Percentage of failed login attempts that occur after hours.
Distribution of after-hours failed login attempts by day of the week and time of day.
# Retrieve login attempts on specific dates:
Number of login attempts on specified dates.
Percentage of successful login attempts on specified dates.
Distribution of login attempts by time of day on specified dates.
# Retrieve login attempts outside the country:
Number of login attempts from outside the company's country.
Percentage of successful login attempts from outside the country.
Top countries with the highest number of login attempts.
# Retrieve employees in Marketing, Sales, and Finance Departments:
Number of employees in each department.
Distribution of employees by department.
Average tenure of employees in each department.
# Retrieving all employees that are not in IT:
Number of employees outside the IT department.
Percentage of employees in non-IT departments.
Distribution of employees by department (excluding IT).

### Conclusion
Our investigation revealed several concerning patterns, including a high volume of failed login attempts from unknown IP addresses and unusual login times for certain employees.
These findings strongly suggest the presence of unauthorized access attempts. To address these issues, we recommend implementing the following measures:
* Strengthen password policies, including enforcing complex passwords and regular changes.
* Implement multi-factor authentication to enhance account security.
* Employ intrusion detection systems to monitor network traffic for suspicious activity.
* Conduct regular security awareness training for employees to prevent social engineering attacks.

As a next step, we propose to develop a machine learning model to automatically detect anomalous login behavior. 
By leveraging advanced analytics, we can enhance our ability to proactively identify and respond to security threats. 

 
