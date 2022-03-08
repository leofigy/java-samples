### The project was created with

```
mvn archetype:generate -DgroupId=xyz.leofigy.monitor -DartifactId=monitor -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

to execute run 
```
mvn package
java -cp target/monitor-1.0-SNAPSHOT.jar xyz.leofigy.monitor.App
Hello World!
```