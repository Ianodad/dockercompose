# Docker Compose Wordpress, Phpadmin Mariadb 

This is a wordpress environment that utilizes docker compose to start multiple containers. 

## Installation

Make sure you have installed Docker && Docker compose

[Install Docker Engine](https://docs.docker.com/engine/install/ubuntu/)
[Install Docker Compose](https://docs.docker.com/compose/install/)


## Setup

```bash
git clone https://github.com/Ianodad/dockercompose.git
```

## Usage

```bash
cd compose

docker-compose up --build # Run docker-compose
```
or
```bash
docker-compose up --build -d # detached mode(run in background) 
```

## Other Commands

```bash
docker-compose stop #Gracefully stop containers
docker-compose kill # 
docker-compose down # stops containers and removes containers, network, volumes, and images created
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)