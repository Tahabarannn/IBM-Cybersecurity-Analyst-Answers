Injection Vulnerability ( Practice Quiz )
Q1. Which operating system is susceptible to OS Command Injection attacks ?

All operating systems are susceptible.
Q2. What is a possible impact of running commands thought OS shell interpreters such as sh, bash, cmd.exe and powershell.exe ?

It makes it easier for a hacker to inject additional commands or arguments.
Q3. True or False: Safe coding practice avoides using OS commands when it can be avoided.

True
Q4. True or False: Safe coding practice always runs commands through a shell interpreter.

False
Q5. True or False: Safe coding practice uses library functions when running OS commands.

True
Q6. True or False: Safe coding practice uses blacklists and avoids the use of whitelists.

False
Ezoic
SQL Injection ( Practice Quiz )
Q1. A hacker tailoring his actions based on the database errors the application displays is an example of which type of SQL Injection attack ?

Error-based
Q2. True or False: Use of prepared statements is an effective mitigation against SQL Injection attacks because it seperates the query structure from the query parameters.

True
Q3. True or False: Native database errors should be hidden from the user to prevent hackers from gaining insight into the internal structure of your application.

True
Q4. True or False: The use of object-relational mapping (ORM) libraries is a dangerous practice that can help hackers conduct successful SQL Injection attacks.

True
Quiz 02
Deep Dive – Injection Vulnerability ( Main Quiz )
Q1. Which of the following statements is True ?

Injection attacks were ranked #1 on the OWASP Top 10 list in 2013 and again in 2017.
Q2. Which vulnerability is being exploited in an OS Command Injection attack ?

Poor user input sanitation and unsafe execution of OS commands.
Q3. What is a simple but effective way to protect against DLL hijacking ?

Always use explicit paths to the commands or library applications.
Q4. True or False: Safe coding practice runs code with the least possible privilege.

True
Q5. True or False: Safe coding practice always specifies relative paths when running applications or using shared libraries.

False
Q6. True or False: Safe coding practice does not let user input reach an OS command unchanged.

True
Q7. A hacker exfiltrating data by injecting an HTTPrequest command is an example of which type of SQL Injection attack ?

Out of Band
Q8. Protecting against SQL Injection attacks by sanitizing user input can be accomplished by which two (2) of the following techniques ?

Use of mapping tables.
Use of whitelists.
Q9. True or False: Limiting database user permissions is an ineffective strategy in preventing SQL Injection attacks since the injected code will run directly against the database regardless of the permission levels that have been set.

False
Q10. Which of the following will help reduce the SQL Injection attack surface ?

Use of stored procedures.
Q11. When developing an application, using NoSQL instead of MySQL will have what effect on the applications susceptibility to SQL Injection attacks ?

It will reduce, but not eliminate, the injection attack surface.
