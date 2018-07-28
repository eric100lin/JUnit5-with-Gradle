# JUnit5-with-Gradle
Build and Test JUnit5 sample with Intelij IDEA and Console Launcher

## Build
Open project and build with IntelliJ IDEA Community Edition 2018.2

## Run with JUnit5 Console Launcher
The jar file "junit-platform-console-standalone-1.2.0.jar" is download from https://repo1.maven.org/maven2/org/junit/platform/junit-platform-console-standalone/1.2.0/

```bash
java -ea -jar junit-platform-console-standalone-1.2.0.jar -cp out\production\classes -cp out\test\classes --scan-class-path
```
