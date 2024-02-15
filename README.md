# Tutorial

- https://www.youtube.com/watch?v=9SGDpanrc8U
  - https://github.com/amigoscode

# Starting

- Visit https://start.spring.io
- Chose dependencies
- Download zip
- I used IntelliJ Idea IDE here

# Adding a dependency later on

- Find dependency on https://mvnrepository.com
- Write to `pom.xml`
- Right click `pom.xml` > Maven > Reload project

# Dependency Injection

- https://kungfutech.edu.vn/bai-viet/spring-boot/component-annotation-va-autowired-annotation
- Autowire: https://www.youtube.com/watch?v=K43qyHJXmWI

# Database

Here I used Postgresql https://www.enterprisedb.com/downloads/postgres-postgresql-downloads

![Screenshot 2024-01-30 181635](https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD/assets/6761422/9edd70bb-6d1c-464d-809d-32b28c605f73)

![Screenshot 2024-01-30 181937](https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD/assets/6761422/a4bd62dd-eee1-4c30-88c4-62896cb8f7a7)

## View DB from IDE

![Screenshot 2024-01-30 183320](https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD/assets/6761422/4b3050b3-ccaa-4528-aea0-30b904d7f1c4)

## DB config

https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD/blob/master/src/main/resources/application.properties

Don't forget to write in the username and password too.

## ORM

https://www.interviewbit.com/blog/jpa-vs-hibernate

# CRUD

```
curl --location 'http://localhost:8080/api/v1/student'

curl --location 'http://localhost:8080/api/v1/student' \
--header 'Content-Type: application/json' \
--data-raw '{
    "name":"Mariam",
    "email":"mariam1@gmail.com",
    "dob":"2000-01-05"
}'

curl --location --request PUT 'http://localhost:8080/api/v1/student/1?name=Maria&email=maria%40gmail.com' \
--data ''

curl --location --request DELETE 'http://localhost:8080/api/v1/student/3' \
--data ''
```

# Let IDE generate API requests

![Screenshot 2024-01-30 193433](https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD/assets/6761422/61ef9e10-6052-4c7d-9618-8bbfc1dfec21)

# Package into JAR

![Screenshot 2024-01-30 195514](https://github.com/Ruslan-Aliyev/Spring-Boot-CRUD/assets/6761422/fd889c4a-b605-448f-bc65-e3ccc67d87cd)

https://stackoverflow.com/questions/62650732/build-jar-and-run-spring-boot-from-cmd/67299008#67299008

# Other tutorials

- https://youtu.be/vtPkZShrvXQ?si=ezdUZLhyKBT1dd8L
