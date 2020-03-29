# .NET CORE - WEB API WITH DOCKER 

## BOOK-STORE

This project was generated with 

*	.net core  3.1
*	Docker 2.2.4
*	Docker Compose Version 3
*	Rider Idea 2019.3


# CREATE PROJECT
Use this command on cli  windows/linux/mac

*	dotnet new webapi  -o docker-test	
*	dotnet build 
*	dotnet publish
*	dotnet run


# DOCKER COMMANDS

*	Docker build -t webApiTest -f Dockerfile .
*	Docker create webApiTest 

#DOCKER COMPOSE
*	Docker-compose build to create the image
*	Docker-compose up  to build container and start service