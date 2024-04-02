Simple maven project 
Steps : 
1. Creating project 
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
2. Adding README file 
3. Running application :
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
This prints hello world in my Local 
4. Pushing this project to github