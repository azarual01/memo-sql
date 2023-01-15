# Docker Init SQL

use :

 - docker 
	 - php 8.1
	 - Apache debian:bullseye
	 - MySql 8.0 
	 

# Installation process

 - ### Step 1 : launch docker-compose
	>		docker-compose up --build
   
  - ### If you need to acces to the differents containers : 
    - ### Connect to the apache container
  
    >             docker exec -it docker_apache bash
	- 
    - ### Connect to the php container
  
    >             docker exec -it docker_php bash
	
      - ### Connect to the mysql container
  
    >             docker exec -it docker_mysql bash
	

# Documentation

 - https://www.docker.com/



# memo-sql    Azarual El-Ghazi

Description:
- Le SQL (Structured Query Language) est un langage permettant de communiquer avec une base de données. Ce langage informatique est notamment très utilisé par les développeurs web pour communiquer avec les données d’un site web. SQL.sh recense des cours de SQL et des explications sur les principales commandes pour lire, insérer, modifier et supprimer des données dans une base.

> Système de gestion de base de données (SGBD)
Chaque SGBD possède ses propres spécificités et caractéristiques. Pour présenter ces différences, les logiciels de gestion de bases de données sont cités, tels que : MySQL, PostgreSQL, SQLite, Microsoft SQL Server ou encore Oracle.
Des SGBD de type NoSQL sont également présentés, tel que Cassandra, Redis ou MongoDB.

-Commande basique:
  -SELECT:  
    > SELECT nom_du_champ FROM nom_du_tableau
    
- Commande basique:
  -SELECT:  
  L’utilisation la plus courante de SQL consiste à lire des données issues de la base de données. Cela s’effectue grâce à la commande SELECT, qui retourne des enregistrements dans un tableau de résultat. Cette commande peut sélectionner une ou plusieurs colonnes d’une table.
  
    > 	- SELECT nom_du_champ FROM nom_du_tableau
    >	- SELECT ville FROM client
    >	- SELECT prenom, nom FROM client
    >   - SELECT * FROM client
    >   - SELECT * FROM table WHERE condition GROUP BY expression HAVING condition { UNION | INTERSECT | EXCEPT } ORDER BY expression LIMIT count OFFSET start
  

