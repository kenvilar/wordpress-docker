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

*if you want to include 'wp-content' folder in your new repo, you should comment the line with text wp-content in .gitignore file.*