# postgresql_pgAdmin_stack

A docker-composer doc for docker PostgreSQL and PGAdmin stack

To init this project:


1 - Create a tree folder:

      - proj_folder
        - PostgreSQL


2 - Create a file with name Dockerfile with no extension. It's where your php server will receive the instructions to add versions or install adds;


3 - Run command:

      docker-compose -f THENAME.yaml up -d


So there are 2 containers on ports:


      0.0.0.0:5432 (Postgresql server);

      0.0.0.0:16543 (pgadmin to administrate your PostgreSQL server);
