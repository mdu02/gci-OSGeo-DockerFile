# gci-OSGeo-DockerFile

Deploying GeoServer on Docker
 
# How I used the repo
 
Download geoserver from [here](https://sourceforge.net/projects/geoserver/files/GeoServer/2.16.1/geoserver-2.16.1-war.zip/download)
 
Unzip the file and copy the geoserver.war file into the repository
 
Run the following commands in terminal
```
docker build ./ -t geoserverbuild
docker run -p 80:8080
```
Using the IP address docker is using (check the beginning of the terminal), go to xxx.xxx.xx.xxx/geoserver
 
