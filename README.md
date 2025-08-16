# Hello Java Maven Project

A simple Java application for Jenkins CI/CD demonstration.

## Project Structure
```
hello-java-maven/
├── src/
│   └── main/
│       └── java/
│           └── HelloWorld.java
├── pom.xml
└── README.md
```

## Build Instructions

### Local Build
```bash
mvn clean package
```

### Jenkins Setup
1. Start Jenkins: `docker run -p 8080:8080 jenkins/jenkins:lts`
2. Configure Maven in Global Tool Configuration
3. Create Freestyle project
4. Set Maven goal: `clean package`
5. Build the project

## Expected Output
```
Hello, Jenkins + Maven!
BUILD SUCCESS
```