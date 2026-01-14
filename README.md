# Food Ordering System

## Description

Example of clean architecture in a food ordering system.
Based on udemy course

## Technologies

- Java
- Maven

## Getting Started


### Prerequisites

- Java 25+
- Maven 3.9+

### Build

To build the project, run:

```sh
mvn clean install
```

To see a dependency graph of the project 
(from: https://github.com/ferstl/depgraph-maven-plugin)

run:

```sh
mvn com.github.ferstl:depgraph-maven-plugin:aggregate -DcreateImage=true -DreduceEdges=false -DclasspathScope=compile "-Dincludes=com.food.ordering.system*:*"
```
