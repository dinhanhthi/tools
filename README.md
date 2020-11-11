# Tools

``` bash
# build container
cd docker
docker-compose -p "tools" up -d
# wait a little bit for it to build at the 1st time

# whenever working
docker start tools_local

# build
docker exec -it tools_local jekyll build
```