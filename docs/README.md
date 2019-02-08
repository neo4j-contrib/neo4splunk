# Neo4j Connector for Splunk

* Support: Community Support
* License: Apache License 2.0
* GitHub: https://github.com/neo4j-contrib/neo4splunk


## Setup for testing with docker-compose

* from neo4splunk/docker start with `docker-compose up`
* login to splunk on localhost:8001
* login to neo on localhost:7474
* in neo execute `:play movie-graph` to generate some graph data
* in splunk go to neo4s app and find the report `Neo4j Movie Data Test` (http://localhost:8001/en-US/app/neo4s/reports)
* if successful: 25 search results should list some actor names

## Configuration

...

## Commands

* neo4j-query statement="" param1="",...
* neo4j-execute statement="" param1="",...
