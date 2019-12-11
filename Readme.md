# Docker For WordPress Theme Testing Enviornment


Clone the repo into any folder.

Go to terminal and run the `docker-compose up -d`. Expecting docker has been already installed at your end. If not please install it.

To know the running container name, run the following command :
`docker ps`

To access the `bash` run the command :
`docker exec -it <container_name> bash`

# It consists of 

1. WordPress Installed
2. MySql Installed with the predefined data. 
3. Predefined Themes like `twentyninteen` etc. 
4. Predefined plugins like `theme check`,`monster widget` etc.


