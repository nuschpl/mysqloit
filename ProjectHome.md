MySqloit is a SQL Injection takeover tool focused on LAMP (Linux, Apache,MySql,PHP) and WAMP (Windows, Apache,MySql,PHP) platforms. It has an ability to upload and execute Metasploit shellcodes through the MySql SQL Injection vulnerability.

Platform supported

1) Linux

Key Features

1) SQL Injection detection using time based injection method
2) Database fingerprint
3) Web server directory fingerprint
4) Payload creation and execution

Requirements

1) FILE privilege
2) Web server and database server must be in the same machine
3) Prior knowledge of the web server directory
4) For the LAMP platform, if the mysqld runs as a non root user, a writeable web server directory is required

Usage

./mysqloit.py -h


Feedback and bug reports contact: muhaimindz@gmail.com