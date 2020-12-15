# Tools

``` bash
# build container
docker-compose -p "tools" -f docker/docker-compose.yml up -d
# wait a little bit for it to build at the 1st time

# whenever working
docker start tools_local

# build
docker exec -it tools_local jekyll build

# get the last info of building
docker container logs tools_local
```