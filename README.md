# Mutilidae & DVWA Web Vulnerabilities Lab

## Objective

The Mutillidae and DVWA Web Vulnerabilities Lab is designed to give students hands-on experience with SQL injection attacks using the Mutillidae web application hosted on Metasploitable 2. The objective is to understand how unsanitized user input can be exploited to compromise backend databases, extract sensitive information, and identify potential security risks in web applications.


### Skills Learned

-Deep understanding of SQL Injection (error-based and union-based).

- Ability to modify configuration files for vulnerable web apps like Mutillidae.

- Familiarity with web application attack vectors and common database vulnerabilities.

- Experience identifying, enumerating, and dumping sensitive data from SQL databases.

- Strengthened offensive cybersecurity and penetration testing methodology.

### Tools Used

- Kali Linux for offensive testing and exploitation.

- Metasploitable 2 (MS2) as the vulnerable target machine.

- Firefox for accessing web apps and executing SQL injection payloads manually.

- Text Editors (nano/sudo nano) for modifying configuration files in Mutillidae.

- SQL Injection commands to enumerate user data, databases, and table structures.

## Steps

Ref 1: Successful Error-Based SQL Injection
Screenshot of the Mutillidae User Info page showing a successful dump of usernames and password hashes (first few entries), along with your Kali VM name showing your ABC123 and last name. Followed the guide from this video.
Screenshot showing a successful dump of the table information for the database
![image](https://github.com/user-attachments/assets/0f40b3ce-2004-4d19-86c8-76895352ef3e)



Ref 2: Dump of User, Database, and Version Info
Screenshot showing successful output of user(), database(), and version() using UNION-based SQL injection. 
![image](https://github.com/user-attachments/assets/448af1c4-c24c-40b4-b4e5-02f83df77cda)



Ref 3: Table Enumeration
Screenshot displaying the result of dumping table names from the database via SQL injection. Example: “users” and “guestbook”.
![image](https://github.com/user-attachments/assets/071f7ec8-f538-499d-9e29-d962c4821f24)



Ref 4: Column Enumeration in Users Table
Screenshot showing names of the columns within the users table, e.g., user, password, email, etc.
![image](https://github.com/user-attachments/assets/13856320-0d80-4f93-9f6d-1b25f38e8177)


Ref 5: Dump of User Table Data
Screenshot showing the dumped credentials (usernames and password hashes) from the users table.
![image](https://github.com/user-attachments/assets/1c7c05a2-e76e-4693-9838-ec7ffb01faa1)

