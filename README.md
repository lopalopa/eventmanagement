# eventmanagement
event management
An Event Management System built with PHP and MySQL that helps users organize, schedule, and manage events efficiently. This application allows event organizers to create and manage events while enabling users to register for and view event details.
Table of Contents
1.	Project Overview
2.	Features
3.	Technologies Used
4.	Installation
5.	Usage
6.	Database Structure
7.	Contributing
8.	License
________________________________________
Project Overview
The Event Management System is designed to streamline the process of creating, managing, and viewing events. Users can register and log in to view events, while administrators can create, update, or delete events. This system is particularly useful for managing community events, workshops, conferences, or any organized gatherings.
Features
•	User Registration and Login: Allows users to register, log in, and manage their profile information.
•	Event Management: Admin users can create, edit, and delete events, including details like date, location, description, and capacity.
•	Booking System: Users can book a spot for events and view their bookings.
•	Event Listings: Display a list of upcoming events with options for filtering and searching.
•	Admin Panel: Admins have access to a dashboard to manage events and user bookings.
•	Responsive Design: Optimized for both desktop and mobile users.
Technologies Used
•	Backend: PHP
•	Database: MySQL
•	Frontend: HTML, CSS, JavaScript, Bootstrap
•	Tools: XAMPP or WAMP for local development
Installation
Follow these steps to set up the project locally:
1.	Clone the Repository:
git clone https://github.com/your-username/event-management-system.git
2.	Set Up Your Environment:
o	Install XAMPP or WAMP if you haven't already.
o	Start Apache and MySQL servers from your control panel.
3.	Configure the Database:
o	Open phpMyAdmin (usually at http://localhost/phpmyadmin).
o	Create a new database (e.g., event_management).
o	Import the SQL file provided in the database folder of this repository to set up the required tables.
4.	Update Database Connection:
o	Open db_connect.php (or any configuration file where database settings are stored).
o	Update the following with your database credentials:
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root'); // or your MySQL username
define('DB_PASSWORD', '');     // your MySQL password
define('DB_NAME', 'eventmanagement'); // your database name
5.	Access the Application:
o	Go to http://localhost/event-management-system in your web browser.
Usage
1.	User Registration and Login:
o	Users can register on the platform, log in, and view events.
o	Admin users can manage event listings and view user registrations.
2.	Admin Panel:
o	Access the admin dashboard (login credentials or registration may be required).
o	From here, admins can add new events, edit existing events, or delete them as needed.
Database Structure
•	Users Table: Stores user information, including id, username, password, email, and role (user/admin).
•	Events Table: Contains details of each event like id, name, date, location, description, and capacity.
•	Bookings Table: Links users to events they've registered for with id, user_id, event_id, and booking_date.
Contributing
Contributions are welcome! If you have suggestions or improvements, please:
1.	Fork the repository.
2.	Create a new branch (git checkout -b feature-name).
3.	Commit your changes (git commit -m 'Add feature').
4.	Push to the branch (git push origin feature-name).
5.	Open a Pull Request.


