# Hosting
# Overview
We provide a simple and fast tool to host vector tiles in mbtiles. 

Sometimes existing software is too complex. It may have some information security concern. It may also be slow to adopt new web technologies such as HTTP/2. Therefore, we developed a simple Express server to host vector tiles and also related files. 

This also realized a hosting service completely isolated from the original datasource. 

The software developed here is not necessarily intended to cover the deployment of the service to the mission-critical situations. The software is originally intended to be used in development and prototyping situation.

# Developed scripts
- [tile-block](https://github.com/hfu/tile-block): A simplest-possible mbtiles-based http/2 vector tile server
