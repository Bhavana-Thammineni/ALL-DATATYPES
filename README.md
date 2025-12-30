# ALL-DATATYPES
Creating the datatypes in the mysql
create database bhavana; ## ctreating the database
use bhavana; # using that database
# creation of table
create table details(
sno int,
rollno bigint,
marks float,
percentage double,
age decimal(2,2),
surname varchar(2),
name char(10),
fullname text,
dob date,
brith time,
passout datetime);
insert into details values(1,410,88,83,23,'g','khushi','gkhushi','2004-12-26','10:30:00','2004-02-26 05:30:00'),
                          (2,410,88,88,23,'g','khushi','gkhushi','2004-12-26','10:30:00','2004-02-26 05:30:00');
desc details; # properties of tables
show tables; # show the tables list
select* from details; # table data box
