# CSEN160 Project Starter

A small Java project template to copy or adapt for a CSEN160 project. It includes a runnable Hello World class, a JUnit 5 test, and folders for project assets and UML diagrams.

## Project layout

```text
src/
  main/java/                 Java application source
  main/resources/
    images/                  Image assets
    sounds/                  Audio assets
    data/                    Other files loaded by the application
  test/java/                 JUnit tests
docs/
  uml/                       UML diagrams and source files
```

Add more resource folders as needed (for example `fonts/`, `videos/`, or `levels/`). Keep UML diagrams in `docs/uml` because they are project documentation rather than files the application loads at runtime.

## Run the example

Open the project in IntelliJ IDEA and run `csen160.starter.HelloWorld`, or use Maven:

```shell
mvn compile
mvn exec:java -Dexec.mainClass="csen160.starter.HelloWorld"
```

Alternatively, run the `main` method from IntelliJ.

## Run JUnit tests

Run `HelloWorldTest` from IntelliJ, or run the test suite with:

```shell
mvn test
```

Place new test classes in `src/test/java`, following the same package structure as the classes they test. Add tests as features are implemented.

## Make it your project

Update the Maven `artifactId`, Java package names, and this README for your project. Put application code in `src/main/java`, tests in `src/test/java`, runtime assets in `src/main/resources`, and design documents such as UML diagrams in `docs/uml`.
