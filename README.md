# ExcelRead
How to read excel sheets using java.
----------------------------
1.MVN archetype:
- generate -DgroupId=xlreading -DartifactId=XlReader -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
- Clone project, move XlReader folder.
- Copy dependancies to pom.xml 
- Copy your class files to xlreading package(src/main/java).

2.Compile:
- mvn compile

3.Run:
- mvn exec:java -Dexec.mainClass="xlreading.XlReading" 
