# 4
create database trabajo1;
use trabajo1;

/* PUNTO 1,2 Y 3 */

create table producto(codigo int unsigned primary key, nombre varchar(100), precio double,codigofabricante int, estado varchar(100));
insert into producto VALUES(1, "Disco duro SATA3 1TB", 86.99, 5,"");
insert into producto VALUES(2, "Memoria RAM DDR4 8GB", 120, 6,"");
insert into producto VALUES(3, "Disco SSD 1 TB", 150.99, 4,"");
insert into producto VALUES(4, "GeForce GTX 1050Ti", 185, 7,"");
insert into producto VALUES(5, "GeForce GTX 1080 Xtreme", 755, 6,"");
insert into producto VALUES(6, "Monitor 24 LED Full HD", 202, 1,"");
insert into producto VALUES(7, "Monitor 27 LED Full HD", 245.99, 1,"");
insert into producto VALUES(8, "Portátil Yoga 520", 559, 2,"");
insert into producto VALUES(9, "Portátil Ideapad 320", 444, 2,"");
insert into producto VALUES(10, "Impresora HP Deskjet 3720", 59.99, 3,"");
insert into producto VALUES(11, "Impresora HP Laserjet Pro M23nw", 180, 0,"");

alter table producto add column pesos int

create table fabricantes (codigo int unsigned primary key, nombre varchar(100));
insert into fabricantes VALUES(1, "Asus");
insert into fabricantes VALUES(2, "Lenovo");
insert into fabricantes VALUES(3, "HP");
insert into fabricantes VALUES(4, "Samsung");
insert into fabricantes VALUES(5, "Seagate");
insert into fabricantes VALUES(6, "Crucial");
insert into fabricantes VALUES(7, "Gigabyte");
insert into fabricantes VALUES(8, "Huawei");
insert into fabricantes VALUES(9, "Xiaomi");


select * from producto
