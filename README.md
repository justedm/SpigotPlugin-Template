# SpigotPlugin-Template

A Spigot plugin template that uses maven and the spigot api.

## Description

Use this template if you want to start creating your spigot plugins without having the need to set everything up everytime.

## Dependencies

Maven: https://maven.apache.org/download.cgi

### Installation and Usage

* Clone the project
* Edit the project packages names to your desire (both main and test)
* Edit the following values in the pom.xml (line 8 to 12):
  - groupId (make sure its the same as the packages names)
  - artifactId (the name of the plugin)
  - version (if you update the plugin)
  - name
* Edit the plugin.yml file inside the resources folder in order to match your project structure
* If you want to change the spigot plugin version you can change it at line 30, remove the current one and select one from the suggestion (1.15.1 to 1.20.1)
* Start creating your plugin and have fun!

## Build jar file

```
mvn clean install
```

The jar output is going to be inside the target folder

