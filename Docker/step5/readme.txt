myphpapp.app
-------------
In this example, I will be setting up a php application using apache that is attached to a
MySQL database. The files will also be volumn controlled and attached to the structure on 
my local machine for active development.

The hostname is created from settings after line 14 within the docker-compose.yml file.

On docker hub, there is mysql image container documentation that will describe different 
settings, for example set up root passwords for your mysql.

This version of MySQL uses 5.7

To view the SQL logs, in your terminal, type 'docker logs myphpapp.app -f' 