# scala-web-bloop-sbt-spring-swagger-hello-world

## Description
A POC for swagger in springframework.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt

## Docker stack
- eed3si9n/sbt

## To run
`sudo ./install.sh -u`
- API http://localhost/hello
- Raw JSON http://localhost/v2/api-docs
- Swagger http://localhost/swagger-ui.html

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://www.javainuse.com/spring/boot_swagger
