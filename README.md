# Docker Kibana for ARM64 
Dockerfile for Kibana that runs on ARM64

## How To Check It Works 
```
git clone https://github.com/RobertRM/docker-kibana-arm64 && cd docker-kibana-arm64
docker-compose up
```
Wait a bit for it to start up then go to http://localhost:5601 and Kibana should load. You can replace
`localhost` with the IP of your server to access it remotely.

## Build Image For Use
Use the bash script:
```
sh ./build_image.sh
```
or build directly
```
docker build -t robertrm/docker-kibana-arm64:7.10.1 .
```
