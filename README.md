# Voting System

This is a simple web-based voting system built using PHP, MySQL, and Bootstrap for a clean and responsive design.

## Features
- User Registration & Login (Secure authentication with password hashing)
- Voting System (Users can vote for candidates)
- Admin Panel (Manage candidates and votes)
- Secure Database Connection (PDO with prepared statements)
- Responsive UI (Bootstrap 5 with a blue and white theme)

## Installation
1. Clone the repository or download the project files.
2. Import the `db_vote.sql` file into your MySQL database.
3. Configure database settings in `Database.php`:
   ```php
   $servername = "localhost";
   $database = "db_vote";
   $username = "root";
   $password = "";
   ```
4. Start your local server using XAMPP or another PHP environment.
5. Open your browser and go to `http://localhost/VOTE`.

## File Structure
- `index.php` - User dashboard
- `login.php` - User login page
- `register.php` - User registration page
- `vote.php` - Voting page
- `logout.php` - Logs out the user
- `admin/` - Admin management pages
- `Database.php` - Database connection file

## Technologies Used
- PHP
- MySQL
- Bootstrap 5
- JavaScript

## Contribution
Feel free to fork this repository and contribute improvements via pull requests.

## License
This project is open-source and free to use.

