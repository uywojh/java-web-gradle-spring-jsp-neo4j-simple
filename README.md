# java-web-gradle-spring-jsp-neo4j-simple

## Description
A jsp springboot java gradle build,
that connects to neo4j database.

## Tech stack
- springboot
  - jsp
- gradle
  - neo4j drivers
  - lombok
  - PostConstruct annotation
- bootstrap
- jquery
- dataTable

## Docker stack
- neo4j:latest
- gradle:jdk11

## To run
`sudo ./install.sh -u`
- [Available](http://localhost)
- [Neo4j webui](http://localhost)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Baeldung Neo4j](https://www.baeldung.com/java-neo4j)
- [Define edges](https://spring.io/guides/gs/accessing-data-neo4j/)
- [Neo4j extra Docker configs](https://paras301.medium.com/initialize-a-neo4j-docker-container-using-cypher-scripts-f4a5ded9ff52)
