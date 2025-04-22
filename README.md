# spring-boot-java-poject
## Creating a Project
```
https://start.spring.io/
```
### In start.spring.io  select the option
```
project – maven
language – java 
spring boot – 3.4.4
packaging – jar
java – 17
dependencies – spring web and spring reactive web
the generate and download

```

## Or but recommended  above process
```
https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
```
```
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5 -DinteractiveMode=false
```

### Create ec2 instance
```
inbound rule 
SMTP 25
HTTPS 443
HTTP 80
RDP 3389
CUSTOM TCP 9090
CUSTOM TCP 8000-9000
CUSTOM TCP 3000-4000
CUSTOM TCP 27017
CUSTOM TCP 5000-6000
CUSTOM TCP 30000-32767
SSH 22
POSTGRESQL 5432


```
```
sudo apt update
sudo apt install openjdk-17-jre -y
sudo apt install maven -y
java -version
mvn –version

```

## To Build & Run This project, follow the steps.

--> Clone the Project

--> Go to Root directly of the project

--> Run "mvn clean package"

--> Run "java -jar target/jar_file_name.jar"

--> Access the Application at IP:8080

Here are some common Maven commands:

- `mvn compile`: Compiles the project's source code.
- `mvn test`: Runs unit tests against compiled code.
- `mvn package`: Packages the compiled code into a distributable format.
- `mvn install`: Installs the package into the local repository.
- `mvn deploy`: Deploys the package to a remote repository.
- `mvn site`: Generates project documentation and reports.
- `mvn site-deploy`: Deploys the generated documentation to a remote web server.  
- `mvn clean`: Executes the clean phase, deleting any previous build outputs. 

## java -jar target/spring-boot-web.jar
