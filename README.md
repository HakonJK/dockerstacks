#Dockerstack on a Debian based VMs running on Synology VMM and Proxmox VE
#Most containers run on the shared proxy-net defined in nginx stack - allows communications between containers (particularly to-from nginx)
#.env files are necessary for the defined variables - or replace variables directly in the docker-compose.yml file.
#.env.examples are provided. Add .env files in the same folder alongside the docker-compose.yml file.
#For use with Portainer, please define environmental variables directly in the environmental variable section below the .yml editor.
