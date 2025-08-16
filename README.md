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

## Expected Output
```
Hello, Jenkins + Ma<img width="1905" height="954" alt="Screenshot 2025-08-16 111841" src="https://github.com/user-attachments/assets/876106a5-5cb9-4c28-aa9d-e5012dbe0a22" />
ven!
BUILD SUCCESS
<img width="1907" height="748" alt="Screenshot 2025-08-16 112242" src="https://github.com/user-attachments/assets/3f5b4a02-5e8a-4cab-9584-23b2f6e98926" />

```
