# How to run wordpress made EMPA website

## 1. Install XAMPP:
- Download and install XAMPP from the official Apache Friends website (https://www.apachefriends.org/index.html) based on your operating system.
- Start the Apache and MySQL services using the XAMPP Control Panel.
## 2. Find EMPA Website Files:
- Obtain a copy of the EMPA website files, including all WordPress files and the database dump (SQL file).
## 3, Import Database:
- Open phpMyAdmin by clicking on the "Admin" button next to MySQL in the XAMPP Control Panel.
- Create a new database (e.g., empa_db) in phpMyAdmin.
- Import the database dump file (empa_db.sql) into the newly created database.
## 4. Configure WordPress:
- Navigate to the folder where you placed the EMPA website files (e.g., C:\xampp\htdocs\empa_website on Windows).
- Open the wp-config.php file in a text editor.
- Update the database connection details:
    - Database name: empa_db
    - Database username: root (default for XAMPP)
    - Database password: Leave blank or use root (default for XAMPP)
- Save and close the wp-config.php file.
## 5. Access EMPA Website:
- Open your web browser and type http://localhost/empa_website (replace empa_website with the actual folder name) in the address bar.
- Follow the on-screen instructions to complete the WordPress setup if prompted (this step might be skipped if the database already contains a configured WordPress installation).
- Once setup or login is complete, you should be able to view and interact with the EMPA website on your local machine.
## 6. Admin Dashboard:
- To access the WordPress admin dashboard, add /wp-admin to your local website URL (e.g., http://localhost/empa_website/wp-admin).
- Log in using the admin credentials (username and password) configured during the WordPress setup or provided with the website files.
