
# ADBMS

ADBMS is database management system that allow users to create, delete and edit DBs using Bash script. 

1) Allow user to create databases, edit and delete database.
2) Allow user to create tables, edit and delete tables.
3) Allow user to select table content.
4) Allow user to delete a record from the table by record primary key.

## Getting Setup

#### Installing project dependencies

- first you need to activate the adbms 
1) open terminal in the directory of the files.
2) run the following commands:
	
```bash
chmod +x activate_adbms
```	

3) in the same terminal

```bash
./activate_adbms
```	

#### Run ADBMS

- now you can run adbms 

```bash
./adbms
```	

## DBMS Manual


- Will show choises list.
- If you want to show this list again just press "enter"

1) create database	3) drop database	5) connect to database
2) show databases	4) Rename database	6) Exit From ADBMs

- first will apper to you list of actions that can choose one of thim 


1 ) create database 

```bash
Enter the name of the database that you want to create.
dbname 
---- dbname created ------
```
--------------------------------------------------------

2) show databases 

>> output 
```bash
------------------Databases---------------------------
dbname db1 db2
------------------------------------------------------
```

3) drop database
```bash
Enter the name of the DataBase that you want to drop it.
 dbname
-----droped-----
```

4) Rename database	
```bash
Enter the old name of the DataBase that you want to rename it.
oldname 
Enter new name
newname
```

6) Exit From ADBMs

5) connect to database

Enter the name of the DataBase that you want to connect it.

- list choies
```bash
1) create table	 3) drop table	  5) select all	   7) exit
2) show tables	 4) insert row	  6) delete row
```

1) create table

```bash 
Note: column ids will created automatically 
Enter the name of the table that you want to create
t1
Enter your column Name
Enter '0' to exit
name 
Please enter your choice of types:
1) number
2) string 
2
Enter your column Name
Enter '0' to exit
0
----created----
```

2) show tables

```bash 
------------------------------------------------------
t1.csv
------------------------------------------------------
```

3) drop table
```bash 
Enter the name of the table that you want to drop it.
t1 
----- t1 drpoed-----

```

4) insert row

```bash 
Note: id will inserted automatically 
Enter the name of the table that you want to inserted in.
t1
Enter name
ahmed
-----Inserted----
```

5) select all	

```bash 
Enter the name of the table that you want to selected all
t1
------------------------------------------------------
ID        | name
1         | ahmed 

------------------------------------------------------
```

6) delete row

```bash 
t1.csv t2.csv t3.csv
------------------------------------------------------
Enter the table name that you want to delete from
t1
Enter the id of the row
1
----deleted---

```

7) exit

```bash 
Your exited from this DataBase

```


