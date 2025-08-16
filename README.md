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
1. Start Jenkins: http://localhost:8080
2. Configure Maven in Global Tool Configuration
3. Create Freestyle project
4. Set Maven goal: `clean package`
5. Build the project

<img width="1905" height="954" alt="Screenshot 2025-08-16 111841" src="https://github.com/user-attachments/assets/eb714cfa-00a4-49e0-8292-8c1c0935b8c2" />
<img width="1907" height="748" alt="Screenshot 2025-08-16 112242" src="https://github.com/user-attachments/assets/64539fc5-4732-4fe4-b54d-5327b59b4e66" />



## Expected Output
```
Hello, Jenkins + Maven!
BUILD SUCCESS


```
