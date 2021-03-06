# Camunda Spring Boot Batch Configuration
Spring Boot example on how to configure the batch seeding and execution for [Camunda](http://docs.camunda.org).

This project has been generated by the Maven archetype
[${archetype-artifactId}-${archetype-version}](https://docs.camunda.org/manual/latest/user-guide/process-applications/maven-archetypes/).

## Show me the important parts!
[CamundaConfiguration.java](src/main/java/com/camunda/consulting/snippet/springboot_config_batch/CamundaConfiguration.java)

## How does it work?
- [Adding Additional Configurations](https://docs.camunda.org/manual/7.9/user-guide/spring-boot-integration/configuration/#adding-additional-configurations)
- [Batch Seeding](https://docs.camunda.org/manual/7.9/user-guide/process-engine/batch/#seed-job)

## How to use it?

### Unit Test
You can run the JUnit test [ProcessTest](src/test/java/com/camunda/consulting/snippet/springboot_config_batch/ProcessTest.java) in your IDE or using:

```bash
mvn clean test
```

### Running the application
You can also build and run the process application with Spring Boot.

#### Manually
1. Build the application using:

```bash
mvn clean package
```
2. Run the *.jar file from the `target` directory using:

```bash
java -jar target/springboot-config-batch.jar
```

For a faster 1-click (re-)deployment see the alternatives below.

#### Maven Spring Boot Plugin
1. Build and deploy the process application using:

```bash
mvn clean package spring-boot:run
```

#### Your Java IDE
1. Run the project as a Java application in your IDE using CamundaApplication as the main class.

### Run and Inspect with Tasklist and Cockpit
Once you deployed the application you can run it using
[Camunda Tasklist](http://docs.camunda.org/latest/guides/user-guide/#tasklist)
and inspect it using
[Camunda Cockpit](http://docs.camunda.org/latest/guides/user-guide/#cockpit).

## Environment Restrictions
Built and tested against Camunda BPM version 7.9.0.

## Known Limitations

## License
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).