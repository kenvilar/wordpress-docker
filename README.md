# wordpress-docker
Docker configuration in WordPress

&nbsp;

Copy the '.env-sample' file and rename the new file as '.env' and then put your passwords and credentials on it.

*if you want to include 'wp-content' folder in your new repo, you should comment the line with text wp-content in .gitignore file.*

Build the project   
`
docker-compose up -d
`

Shutdown and cleanup (removes the containers, default network, and the Wordpress database)    
`
docker-compose down --volumes
`

But if you want to remove the containers and default network but want to preserve the Wordpress database    
`
docker-compose down
` 
