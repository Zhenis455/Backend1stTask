# Backend1stTask — Spring Core Dependency Injection (2025)

Early Java 17 / Spring Framework practice. The program creates `Student` objects using a Spring application context and prints their details in the terminal.

## How it works
`Main.java` initializes `ProjectConfig`, retrieves a `Student` bean, and calls `student.showInfo()`.

## Run (Windows/macOS/Linux)
Requires JDK 17 and Maven 3.9+.
```bash
git clone https://github.com/Zhenis455/Backend1stTask.git
cd Backend1stTask
mvn clean verify
mvn org.codehaus.mojo:exec-maven-plugin:3.5.0:java -Dexec.mainClass=org.example.Main
```

There is **no database, frontend, or web server**. GitHub Actions validates the Maven build on every push.

This is a learning mini-project; other repositories `City` and `spring` may contain related variants of the same coursework.
