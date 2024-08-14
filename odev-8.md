    create database test
    use test

    create table employee
    (
    id int identity(1,1) primary key,
    name varchar(50),
    birthday date,
    email VARCHAR(100)
    );

    select * from employee

    update employee 
    set name = 'Eyüp',
    birthday = '2001-08-28'
    where id = 1;

    update employee
    set birthday = '2004-06-30'
    where name = 'Aurora Mundie'

    update employee
    set email = 'eyp@gmail.com'
    where id = 1

    update employee
    set name = 'Paul Walker'
    where name ='Eyüp'

    delete from	employee where name ='Dom Gornall'

    delete from employee where id = 48

    delete from employee where name like('P%')

    delete from employee where id > 5