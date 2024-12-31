# A simple archetype for Java projects

A simple `maven-archetype` for Java projects with basic style checks (using Spotless) and predefined publishing configuration for Maven central.

## Build the archetype
```
mvn clean install
```

## Generate an archetype
```
mvn archetype:generate -DarchetypeGroupId=com.github.zabetak -DarchetypeArtifactId=java-archetype -DarchetypeVersion=1.0-SNAPSHOT -DartifactId=my-super-utils -DgroupId=com.github.zabetak
```
