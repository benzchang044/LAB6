# LAB6
Circular-Replication-master
create database LAB6;
use LAB6;
CREATE TABLE users(id INT AUTO_INCREMENT,
	name VARCHAR(30),
	datum TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
	PRIMARY KEY(id));
INSERT INTO users(name) VALUES('Sivuch');
select * from users;


master_host='10.0.0.8',
master_port=3306,
master_user='replicator',
master_password='123456',
master_log_file='mariadb-bin.000017',
master_log_pos=424;
