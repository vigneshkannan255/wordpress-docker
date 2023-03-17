<div align="center">
		<img width="120" height="120" src="https://github.com/vigneshkannan255/wordpress-docker/blob/37917425c8b4f073776c1da02da8167d8981035a/images/wordpress.png" alt="logo"
	</a>
		<img width="230" height="120" src="https://github.com/vigneshkannan255/wordpress-docker/blob/37917425c8b4f073776c1da02da8167d8981035a/images/Docker.png" alt="logo"/>
  </a>
</div>

<h1 align="center">  Wordpress + Docker </h1>


<h3 align="center"><b>This script is used to run wordpress on docker container with two services.</b></h3>

## Prerequisites

`Linux packages`

```
▶ apt install docker.io docker-compose
```
`clone`

```
▶ git clone https://github.com/vigneshkannan255/wordpress-docker.git
▶ cd wordpress-docker
```
`Note: Before running below command please change the IP address and database credentials in docker-compose.yaml`

## Docker compose

This command is used to make the [docker compose](https://docs.docker.com/compose/) up with detached mode.

`Note: Always we need to run docker-compose command inside the directory where we place the docker-compose.yaml file`

```
▶ docker-compose up -d
```
## After running the above command 

- [x] It will pull the docker image from the [official repository](https://hub.docker.com/search?image_filter=official&q=) and store it in local.
- [x] It will start the container with the pulled images.
- [x] It will create the required volumes to store data.
- [x] It will create the required network.

## Images and Services

- [x] [Wordpress](https://hub.docker.com/_/wordpress)
- [x] [Mysql](https://hub.docker.com/_/mysql)

## Docker commands

command used to check the docker process.
```
▶ docker-compose ps -a
```

command used to check the bring down the container.
```
▶ docker-compose stop 
```

command used to down all whole docker compose.
```
▶ docker-compose down
```


commands used to check the available docker images, container, volume and network.

```
▶ docker image ls
▶ docker container ls
▶ docker volume ls
▶ docker network ls
```
