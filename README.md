# Minimal Java 8 Maven Archetype 

[![Build Status](https://travis-ci.org/spodin/j8-minimal.svg?branch=master)](https://travis-ci.org/spodin/j8-minimal)
[![License](https://img.shields.io/badge/license-Unlicense-blue.svg)](LICENSE)
[![Maven Central](https://img.shields.io/maven-central/v/com.vasiliyspodin/j8-minimal.svg)](http://mvnrepository.com/artifact/com.vasiliyspodin/j8-minimal)

The project is a minimal Maven archetype for plain Java 8 application.

This artifact is available via the Maven Central Repository and can be automatically installed using the `mvn archetype:generate` invocation:

`mvn archetype:generate -Dfilter=com.vasiliyspodin:j8-minimal`

## Generated Project

### Included Dependencies

- [JUnit 4.12](https://mvnrepository.com/artifact/junit/junit/4.12)

### Structure

```
.
├── .gitignore
├── pom.xml
├── README.md
└── src
    ├── main
    │   ├── java
    │   │   └── {package}
    │   │       └── Application.java
    │   └── resources
    └── test
        └── java
            └── {package}
                └── ApplicationTest.java
```

## Prerequisites

- Oracle JDK 8
- Maven 3

## Installation

Clone repository and execute `./mvnw` or `mvnw.cmd`, depending on your operating system.

See [root POM](pom.xml) for `groupId`, `artifactId`, and `version` coordinates.