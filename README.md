# Secure Login with SQLi Prevention PHP Code:
This code has a secured login via PHP and SQL and prevents SQL Injection of any level.
This code has a PHP function called mysqli-real_escape_string() which takes in two parameters:
1. Your database connection variable (Like $conn, $con etc).
2. The string you want to remove hashes from.
What this function does is, it removes all the special characters from the strings so that the password is not commented out and 
therefore prevents SQL Injection.

Then it connects to a database named test (in XAMPP) and table named login. You can change the names of these variables into
anything you like as long as the database and tables are present.

# Demo:
<img width="254" alt="image" src="https://user-images.githubusercontent.com/108524555/226086519-54f0a14a-63f0-40ee-984b-10a6c9683401.png">
Valid Username: testName 
Valid Password: 12345

# Before using PHP Function (SQL Injection Attack):
<img width="241" alt="image" src="https://user-images.githubusercontent.com/108524555/226086566-b2c7e827-f9fa-411a-b087-832ec0a6d776.png">
<img width="233" alt="image" src="https://user-images.githubusercontent.com/108524555/226086668-47ecc885-d18a-4040-9e52-66474337cd3c.png">

# After using SQLi Prevention PHP Code:
<img width="491" alt="image" src="https://user-images.githubusercontent.com/108524555/226087087-0d8d407e-f5dd-409a-bc11-7e9c95471212.png">
<img width="241" alt="image" src="https://user-images.githubusercontent.com/108524555/226086566-b2c7e827-f9fa-411a-b087-832ec0a6d776.png">
<img width="232" alt="image" src="https://user-images.githubusercontent.com/108524555/226087135-85829d36-395f-4a41-aef0-4fd4dad62129.png">


Thank You
