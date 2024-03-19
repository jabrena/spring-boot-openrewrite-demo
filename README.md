# spring-boot-openrewrite-demo

## How to test in local?

```
mvn rewrite:run
```

## References

- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot/
- https://start.spring.io/
- https://docs.openrewrite.org/recipes/java/spring/boot3/upgradespringboot_3_0

## Tools

```
sdk install springboot
spring init --list
spring init --build "maven" -j "21" -l "java" -d "web, actuator, devtools" -x -f
```