Use Source Command on MYSQL Shell or Command Line to execute a .sql file
------------------------------------------------------------------------
Example:
--------
SOURCE C:\Users\H P\Documents\MKK\mkk_database.sql

Use mysql connection string on terminal and stdin from file to execute a .sql file
---
Syntax
---

mysql -h<host> -P<port> -u<user> -p<password> DATABASE_NAME < filename.sql

---

Host is not required if mysql server is running on localhost
--
mysql -uroot -proot mkk < "C:\Users\H P\Documents\MKK\mkk_database.sql"

Example
---

C:\Users\H P>mysql -uroot -proot mkk < "C:\Users\H P\Documents\MKK\mkk_database.sql"
mysql: [Warning] Using a password on the command line interface can be insecure.
