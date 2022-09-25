# crudPhp
Crud bootstrap Php Mysql

Un crud simple con bootstrap 5 Php 7 Mysql jquery

Necesitaremos crear una base de datos, a continuacion dejo un comando para crear la db


CREATE DATABASE `crud`;

USE `crud`;

CREATE TABLE `articulos` (
  `codigo` int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
  `descripcion` varchar(50) NOT NULL,
  `precio` float NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
