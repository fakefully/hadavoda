Also, id should have auto increment as primary key and borrowed_by should be NULL by default

DBNAME - softlab

users table
-----------
1	id Primary	int(50)			No	None		AUTO_INCREMENT	Change Change	Drop Drop	
2	username	varchar(100)	utf8mb4_general_ci		No	None			Change Change	Drop Drop	
3	email	varchar(100)	utf8mb4_general_ci		No	None			Change Change	Drop Drop	
4	password	varchar(100)	utf8mb4_general_ci		No	None			Change Change	Drop Drop	

books table
------------
1	id Primary	int(50)			No	None		AUTO_INCREMENT	Change Change	Drop Drop	
2	title	varchar(100)	utf8mb4_general_ci		No	None			Change Change	Drop Drop	
3	author	varchar(100)	utf8mb4_general_ci		No	None			Change Change	Drop Drop	
4	publication_year	year(4)			No	None			Change Change	Drop Drop	
5	borrowed_by	varchar(100)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	

