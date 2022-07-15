# Online Book Store
<br/><b style="color:red">Welcome to Online Book Store</b>

<b>NOTE:- The Project Files are kept under <a href="https://github.com/shashirajraja/onlinebookstore/tree/gh-pages">gh-pages</a> and <a href="https://github.com/shashirajraja/onlinebookstore/tree/J2EE">J2EE</a> Branch!</b><br/>

#### To View First Front Page Design of this website
- For Selling books online.
- Maintaining books selling history.
- Adding and managing books.
- User Friendly.
- For Implemention of Generic Servlets in Java.
- This is a Mini-project developed using Java, Jdbc, And Generic Servlets.

<span style="color:blue">**Admin Have Following Access for this online store site:-**</span>
- Add New Books.
- View Books Available.
- Remove Books.
- Increase Books Amount.

<span style="color:blue">**Users Have Following Access for this online store site:-**</span>
- Create New Account or Register.
- Login.
- View Available Books.
- Select Books to Buy.
- Select Books Quantity.
- Buy Books.
- Get Payment Receipt.

### Technologies used:-
1. Front-End Development:
- Html.
- Css.
- Javascript.
- 

2. Back-End Development
- Java [JDK 8+]
- JDBC
- Servlet
- MySQL
- Apache Maven

3. Database used.
- MySql

### ==== Software And Tools Required ====
- MySQL
- Eclipse [Enterprise Edition]
- Java [JDK 8+]
- Tomcat v8.0+
- Apache Maven

Note:- This is a Sample Project, So we have used only Generic Servlet and not taken care for Security.

### =============== Dummy Database Initialization =====================

STEP 1: Open MySQL Command Prompt or MySQL Workbench

STEP 2: Login to the root user as : ```mysql -u <username> -p <password>```

STEP 3 :Copy paste the following MySql Commands:
```MySQL
create database onlinebookstore;

use onlinebookstore;

create table books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

create table users(username varchar(100) primary key,password varchar(100), firstname varchar(100),lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

insert into books values('10101','Programming in C','James k Wick',500,5);
insert into books values('10102','Learn Java','Scott Mayers',150,13);
insert into books values('10103','Database Knowledge','Charles Pettzoid',124,360);
insert into books values('10104','Let us c++','Steve Macclen',90,111);
insert into books values('10105','Success Key','Shashi Raj',5000,15);
insert into users values('User','Password','First','User','My Home','42502216225','User@gmail.com',2);
insert into users values('Admin','Admin','Mr.','Admin','Haldia WB','9584552224521','admin@gmail.com',1);
insert into users values('shashi','shashi','Shashi','Raj','Bihar','1236547089','shashi@gmail.com',2);

commit;
```

