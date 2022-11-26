Tables to be added in Database:


create table invoice_id_ecotourism(id number(10));
create table signin_log_ecotourism(emailid varchar(100));
create table amounts_ecotourism(place varchar(100), bus number(10), train number(10), flight number(10));
create table users_ecotourism(username varchar(100), emailid varchar(100), password varchar(100), question varchar(100), answer varchar(100));
create table orders_ecotourism(invoice_id number(10), invoice_date varchar(100), name varchar(100), emailid varchar(100), place varchar(100), transport varchar(100), travel_date varchar(100), amount number(10), persons number(10), total number(10));

insert into invoice_id_ecotourism values(1);
insert into amounts_ecotourism values('andaman', 0, 0, 40000);
insert into amounts_ecotourism values('coorg', 4700, 8000, 16000);
insert into amounts_ecotourism values('goa', 10000, 16000, 20000);
insert into amounts_ecotourism values('ladakh', 18000, 25000, 35000);
insert into amounts_ecotourism values('manali', 19000, 25000, 36000);
insert into amounts_ecotourism values('nainital', 6000, 10000, 15000);
insert into amounts_ecotourism values('ooty', 8000, 10000, 15000);
insert into amounts_ecotourism values('udaipur', 5000, 9000, 15000);
