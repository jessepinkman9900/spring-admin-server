## Spring Admin

### Usage

#### Server

```shell
./gradlew bootRun
```

#### Client

- add dependency

    ```xml
    <dependency>
        <groupId>de.codecentric</groupId>
        <artifactId>spring-boot-admin-starter-client</artifactId>
        <version>2.4.1</version>
    </dependency>
    ```

- add in `application.properties`

    ```
    spring.boot.admin.client.url=http://localhost:8031
    ```

### Resources

- https://www.baeldung.com/spring-boot-admin
- https://codecentric.github.io/spring-boot-admin/current/ [Version 2.4.0-SNAPSHOT]
