# HR Dashboard - Data Generator 📊

Welcome to the HR Dashboard Dummy Data Generator project! This script generates realistic dummy data simulating various human resources (HR) metrics, ideal for building, testing, or demonstrating HR dashboards and analytics systems.

## Project Overview 🚀
This Python script creates synthetic HR data that mimics real-world employee datasets. The generated data includes employee demographics, job roles, salaries, attendance patterns, and performance ratings, making it perfect for testing HR analytics applications or visualizations.

## Key Features 📋
### Employee Demographics 👥
The generated dataset includes:

Employee ID: Unique identifiers for each employee.
Name: Randomly generated names (gender-based).
Gender: Simulated male/female ratio with weighted distribution.
City & Province: Locations from various Indonesian cities with weighted distributions.
Latitude/Longitude: Simulated geographic coordinates for each city.
Birth Date: Randomly assigned dates within a specific age range (21 to 55).

### Job Information 🏢
Department: Employees are randomly assigned to one of several departments (HR, IT, Sales & Marketing, etc.).
Job Title: Titles are assigned based on the department (e.g., Software Developer, HR Assistant, etc.).
Education Level: Random education levels are chosen based on job titles (e.g., SMA/SMK, Diploma, Sarjana (S1)).
Hire Date: Random hire dates within the last 10 years.

### Compensation 💰
Base Salary: Salary ranges based on job titles (e.g., Software Developer, HR Assistant, etc.).
Adjusted Salary: Calculated based on years of tenure, with a yearly adjustment factor.
Performance Rating: Randomized performance ratings (e.g., Excellent, Good, Needs Improvement).
Overtime: Employees may be flagged for overtime (Yes/No).

### Employee Status 🔄
Termination Date: Random termination dates for employees who are marked for termination, simulating potential employee turnover.

## Project Structure 📂
Data Generation Script: A Python script that generates dummy employee data with various HR metrics.
Output: A CSV file (full_employee_data.csv) containing the generated employee data, ready for use in HR dashboards or analytics tools.
Libraries: The script relies on the following Python libraries:
pandas for data handling and manipulation.
random for generating random data.
Faker for generating realistic fake names and dates.
datetime for handling date-related operations.

## Output 🎉
The generated dataset includes the following columns:

### Column Name	Description
employee_id	Unique employee identifier (e.g., JKM1234)

name	Employee's full name

gender	Employee's gender (Male/Female)

city	City where the employee is located

province	Province of the employee's location

latitude	Latitude of the employee's city

longitude	Longitude of the employee's city

department	Department the employee belongs to

job_title	Employee's job title

hire_date	Date when the employee was hired

birth_date	Employee's birthdate

termination_date	(Optional) Date of employee termination

education_level	Employee's education level

salary	Employee's adjusted salary

performance_rating	Performance rating of the employee (Excellent, Good, etc.)

overtime	Whether the employee works overtime (Yes/No)


## 📫 Contact
If you have any questions or want to collaborate, feel free to reach out!
**LinkedIn**: https://www.linkedin.com/in/ahmad-zaenal-hayat/
**Email**: a.zaenalhayat@gmail.com

Feel free to explore the scripts and insights, and let's harness the power of data together! 🌟
