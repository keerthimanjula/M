# M

mvn archetype:generate -DgroupId=com.mrit -DartifactId=HelloWorld -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn exec:java -Dexec.mainClass=”com.mrit.App”
