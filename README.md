
# CUBRID JDBC Driver
[![Maven Central](https://img.shields.io/maven-central/v/io.github.srltas/cubrid-jdbc-driver?label=Maven%20Central)](https://central.sonatype.com/artifact/io.github.srltas/cubrid-jdbc-driver)
[![Javadoc](https://javadoc.io/badge2/io.github.srltas/cubrid-jdbc-driver/javadoc.svg)](https://javadoc.io/doc/io.github.srltas/cubrid-jdbc-driver/latest/index.html)


## 💡 Why this project?
CUBRID maintains its [own internal Maven repository](https://maven.cubrid.org/cubrid/cubrid-jdbc/) for the JDBC driver, but using it requires developers to manually add a repository entry to their `pom.xml` or `settings.xml`.

This repository allows developers to use the CUBRID JDBC driver in `Maven` or `Gradle` build environments without any additional repository configuration.

## 📦 Maven / Gradle Dependency
### ✅ Maven
``` xml
<dependency>
  <groupId>io.github.srltas</groupId>
  <artifactId>cubrid-jdbc-driver</artifactId>
  <version>x.y.z.build</version>
</dependency>
```

### ✅ Gradle(Groovy DSL)
``` groovy
implementation 'io.github.srltas:cubrid-jdbc-driver:x.y.z.build'
```

## 📚 Javadoc
- [View API Documentation (javadoc.io)](https://javadoc.io/doc/io.github.srltas/cubrid-jdbc-driver/latest/index.html)

## 🤝 Credits
- Original driver maintained by the [CUBRID Foundation](https://www.cubrid.org)
