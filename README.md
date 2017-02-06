# Minimal Java 8 Maven Archetype 

The project is a minimal Maven archetype for plain Java 8 application.

[![Build Status](https://travis-ci.org/spodin/j8-minimal.svg?branch=master)](https://travis-ci.org/spodin/j8-minimal)
[![license](https://img.shields.io/badge/license-Unlicense-blue.svg)](LICENSE)

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
    │   │   └── {com}
    │   │       └── {company}
    │   │           └── Application.java
    │   └── resources
    └── test
        └── java
            └── {com}
                └── {company}
                    └── ApplicationTest.java
```

## Prerequisites

- Oracle JDK 8
- Maven 3

## Installation

Clone repository and execute `./mvnw` or `mvnw.cmd`, depending on your operating system.

See [archetype-catalog.xml](archetype-catalog.xml) for `groupId`, `artifactId`, and `version` values.