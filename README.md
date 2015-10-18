Xtreme Vulnerable Web Application (XVWA) 
=========================================
XVWA is a badly coded web application written in PHP/MySQL that helps security enthusiasts to learn application security.  It’s not advisable to host this application online as it is designed to be “Xtremely Vulnerable”. We recommend hosting this application in local/controlled environment and sharpening your application security ninja skills with any tools of your own choice. It’s totally legal to break or hack into this. The idea is to evangelize web application security to the community in possibly the easiest and fundamental way. Learn and acquire these skills for good purpose. How you use these skills and knowledge base is not our responsibility. 

XVWA is designed to understand following security issues. 

SQL Injection – Error Based 
SQL Injection – Blind
OS Command Injection
XPATH Injection 
Unrestricted File Upload
Reflected Cross Site Scripting 
Stored Cross Site Scripting 
DOM Based Cross Site Scripting 
Server Side Request Forgery (Cross Site Port Attacks) 
File Inclusion 
Session Issues 
Insecure Direct Object Reference 
Missing Functional Level Access Control 
Cross Site Request Forgery (CSRF)
Cryptography 
Unvalidated Redirect & Forwards
Server Side Template Injection

Good Luck and Happy Hacking!

Disclaimer 
=========================================
Do not host this application on live or production environment. XVWA is totally vulnerable application and giving online/live access of this application could lead to complete compromise of your system. We are not responsible for any such bad incidents. Stay safe ! 

Copyright
=========================================
This work is licensed under the Creative Commons Attribution 4.0 International License. 
To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

Instruction 
=========================================
XVWA is hustle free to setup. You can set this up on windows, linux or Mac. Following are the basic steps you should be doing on your Apache-PHP-MYSQL environment to get this working.  Let that be WAMP, XAMP or anything you prefer to use. 

Copy the xvwa folder in your web directory. Make sure the directory name remains xvwa itself. 

Make necessary changes in xvwa/config.php for database connection. Example below: 

<code>
$XVWA_WEBROOT = ''; 

$host = "localhost"; 

$dbname = 'xvwa'; 

$user = 'root'; 

$pass = 'root';
</code>

Make following changes in PHP configuration file

<code>
file_uploads = on 

allow_url_fopen = on

allow_url_include = on
</code>
Access the application on : http://localhost/xvwa/

Setup the database and table by accessing http://localhost/xvwa/setup/

The login details

<code>
admin:admin

xvwa:xvwa

user:vulnerable
</code>

About 
=========================================
XVWA is intentionally designed with many security flaws and enough technical ground to upskill application security knowledge. This whole idea is to evangelize web application security issues. Do let us know your suggestions for improvement or any more vulnerability you would like to see in XVWA future releases. 

Authors:

@s4n7h0 https://twitter.com/s4n7h0 

@samanL33T https://twitter.com/samanl33t 
