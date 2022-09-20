## Whistle Blower Files 


# To Install PHP on your local PC:
<br/>
Mac - 
<br/>

```
curl -s https://php-osx.liip.ch/install.sh | bash -s 7.3

```
<br/>
After The Installation is complete, open the terminal and go the path of the folder that you are trying to open in php server.
<br/>
To Start the Server, Enter this in the terminal

```
php -S 127.0.0.1:8080

```

<br/>
Go to Your brower and enter the path of the file you want to open.
<br/>

```
127.0.0.1:8080/path/to/file

```

<br/>
Install mysql on your local computer and include the path of the mysql files in the primary paths file of your pc

<br/>
Start the mysql server by using 
```
mysql.server start

```
<br/>
Then Enter
```
mysql

```
<br/>
To Start the Server.

<br/>
Create the whistle database and enter 

```
use whistle;

```
<br/>
Find the path to the .sql file we have and enter the following line in mysql
<br/>
```
SOURCE path/to/file.sql;

```
<br/>
This will load the database into the server
<br/>

You are ready to use your PHP Server.
