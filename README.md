# Basic-Data-Entry-with-PHP
Simple PHP form to insert name and age into a MySQL database.
## Abstract
This project presents a simple web-based application developed using HTML, PHP, and MySQL. It allows users to submit their name and age through an HTML form, with the submitted data being processed via PHP and stored in a MySQL database. The application serves as a foundational example of full-stack web development and demonstrates the basic flow of data from client input to database storage.

## Objectives
- To design a user-friendly web form for data collection.
- To implement server-side data handling using PHP.
- To establish a connection between the web application and a MySQL database.
- To demonstrate data insertion into a relational database using SQL through PHP.

## Technologies Used
- **Frontend:** HTML5  
- **Backend:** PHP 8.x  
- **Database:** MySQL (via phpMyAdmin)  
- **Server:** XAMPP (Apache & MySQL)
## Functional Description
The application consists of two primary files:
- `form.html` – Contains a web form that captures user input (name and age).
- `y.php` – A PHP script that receives the POST request, connects to the database, and inserts the submitted data.
The user accesses the form via a web browser, enters their name and age, and upon submission, the data is sent to the server where it is processed and saved in the database.

## Database Configuration
A MySQL database named `digital` is used for data storage. The following SQL command creates the appropriate table:

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT
);
Creat By ENG: Majd Omar Bagazi
