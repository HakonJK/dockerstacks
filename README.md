#Dockerstack on a Debian based VM running on Synology VMM
#Most containers run on the shared proxy-net defined in nginx stack - allows communications between containers (particularly to-from nginx)
#.env files are necessary for the defined variables - or replace variables directly in the docker-compose.yml file.
#.env files are not part of this repo, they are private and defined/stored in each folder along with the docker-compose.yml file.
#For use with Portainer, please define environmental variables directly in the environmental variable section below the .yml editor.
