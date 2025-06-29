# LangChain4J Spring Boot Project

This repository contains a minimal Spring Boot setup for experimenting with [LangChain4J](https://github.com/langchain4j/langchain4j).

## Building and Running

Use Maven to build and run the application:

```bash
mvn spring-boot:run
```

The application exposes a simple HTTP endpoint at `/` that returns a greeting.

Before using LangChain4J integrations (such as OpenAI), configure any required API keys in `src/main/resources/application.properties`.
