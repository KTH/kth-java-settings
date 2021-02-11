# Integral settings 

## Introduction
This repo contains the KTH Checkstyle configuration for Team Integrations projects. 

## Configuration
Add this to your projects pom.xml

```xml
<plugin>
  <groupId>org.apache.maven.plugins</groupId>
  <artifactId>maven-checkstyle-plugin</artifactId>
  <version>3.1.1</version>
  <executions>
    <execution>
      <phase>process-sources</phase>
      <goals>
        <goal>check</goal>
      </goals>
    </execution>
  </executions>
  <configuration>
   <configLocation>https://raw.githubusercontent.com/KTH/kth-java-settings/main/kth_checkstyle.xml</configLocation>
    <failsOnError>true</failsOnError>
  </configuration>
</plugin>
```

