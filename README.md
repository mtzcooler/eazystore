# eazystore
Course "Become a Java Full Stack Developer with React &amp; Spring Boot" offered by Eazy Bytes

## Backend application

### Instructions
On IntelliJ, build with Ctrl+F9 and then run it by hitting play.

### Database
Mount docker image with the following command:
`docker run -p 3306:3306 --name eazystoredb -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=eazystore -v ~/eazystore-data:/var/lib/mysql -d mysql`

