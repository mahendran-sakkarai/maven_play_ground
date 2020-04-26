**Archetype quick start**
----
Initial command:

> mvn archetype:generate -DgroupId=groupid -DartifactId=artifactid -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=booleanValue

Ex:
> mvn archetype:generate -DgroupId=com.github.mahendran-sakkarai -DartifactId=MavenQuickStartGenerator -DarchetypeArtificatId=maven-archetype-quickstart -DinteractiveMode=false

It'll automatically generatte the file structure.

**To compile**
> mvn clean compile

Run the app
> cd target\classes\
> java com.github.mahendran_sakkarai.App

**To package**
> mvn package

To run the app:
> java -classpath target\MavenQuickStartGenerator-1.0-SNAPSHOT.jar com.github.mahendran_sakkarai.App