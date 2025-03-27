# Stock Quotes Service
## Use SDKManRC
https://sdkman.io/usage/
### Set Java version
```
sdk env
```

### On Windows (not tested, not recommended)
In Intellij in "Project Structure"
- Set SDK to i.e. temurin-17
- Set language level to java 17 LTS
- Set JAVA_HOME env for jdk >= 17

## Commands
### Build app

```
./gradlew clean build
```

### Run app
```
./gradlew bootRun
```
Or simply from Intellij. Run Application class (No build is needed).

### Build Docker Image
https://bmuschko.github.io/gradle-docker-plugin/current/user-guide/#spring_boot_application_plugin
```
./gradlew dockerBuildImage
```

## Swagger
http://localhost:8094/swagger-ui/index.html

### Annotations
@Tag - use on class level to describe controller  
@Operation - use on method level to describe endpoint  
@ApiResponse - use to define response codes

