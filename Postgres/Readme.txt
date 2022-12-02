to start / restart containers in docker-compose.yml
---------------------------------------------------
docker-compose up -d 

to run bash in postgres container
---------------------------------  
docker exec -it <container_id> bash 


to login to db
--------------
psql -U <username>



to list all databases
---------------------
\list 


to connect to specific database
-------------------------------
\c <database_name>



to list all tables
------------------
\dt




PGAdmin
-------
If first time, go to Register -> Server



in WSL, enter and use this as Host:
docker inspect <container_id> | grep IPAddress 