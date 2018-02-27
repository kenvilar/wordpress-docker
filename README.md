# wordpress-docker
Docker configuration in WordPress

Build the project   
`
docker-compose up -d
`

Shutdown and cleanup    
`
docker-compose down --volumes
`

Copy the '.env-sample' file and rename the new file as '.env' and then put your passwords and credentials on it.

*if you want to include 'wp-content' folder in your new repo, you should comment the line with text wp-content in .gitignore file.*