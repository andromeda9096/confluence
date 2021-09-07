# test change
## Atlassian confluence full on docker

### Bash
```
docker volume create --name confluence

docker run -v confluence:/var/atlassian/application-data/confluence --name="confluence" --restart unless-stopped -d -p 6090:8090 -p 6091:8091 andromeda9096/confluence-wiki:0.0.2
```
### Open in your Browser

http://hostip:6090
