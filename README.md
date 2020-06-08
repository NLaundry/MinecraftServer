# MinecraftServer
Server backups

## Running with Docker

### Installing Docker

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04

### Running with Docker

docker run -it -p 25565:25565 -e MEMORY=4G EULA=TRUE --name mc -v /home/nathan/sideProjects/MinecraftServer/Minecraft:/data itzg/minecraft-server:latest
docker start mc
docker stop mc
