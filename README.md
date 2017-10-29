# Gradle Java
This is a simple Gradle build file for building a Java hello world project.

## Dependencies
- Joda Time library : This library was used so the application can print the current date and time.

## Repository
The joda-time depencency was resolved by the Maven Central repository (https://search.maven.org/)

## Built Project
A Gradle Wrapper shell & batch script were added allow you to run a Gradle build without requiring that Gradle be installed on your system.

Run the wrapper script to perform the build task.
```
$./gradlew build
```

## Run Project
Gradle’s application plugin was included in the build.gradle file to make the code runnable.
```
$ ./gradlew run
```

### Sample Output
```
> Task :run
The current time is: 16:53:49.715
Hello world!


BUILD SUCCESSFUL in 0s
2 actionable tasks: 1 executed, 1 up-to-date
```

