# java-web-bloop-sbt-spring-jsf-h2-simple

## Description
A jsf springboot java bloop-sbt build,
that connects to in memory h2 database.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- springboot
  - jsf
- bloop-sbt
  - h2 drivers
  - lombok
  - PostConstruct annotation
- bootstrap
- jquery
- dataTable

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
Available http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
