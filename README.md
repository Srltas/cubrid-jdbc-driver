
# CUBRID JDBC Driver

[![Maven Central](https://img.shields.io/maven-central/v/io.github.srltas/cubrid-jdbc-driver?label=Maven%20Central)](https://central.sonatype.com/artifact/io.github.srltas/cubrid-jdbc-driver)
[![Javadoc](https://javadoc.io/badge2/io.github.srltas/cubrid-jdbc-driver/javadoc.svg)](https://javadoc.io/doc/io.github.srltas/cubrid-jdbc-driver/latest/index.html)

> JDBC driver for connecting to [CUBRID](https://github.com/CUBRID/cubrid) databases.
> The goal of this project is to distribute the official CUBRID JDBC driver to Maven Central.

---

## 💡 Why this project?

CUBRID maintains its own internal Maven repository for the JDBC driver, but using it requires developers to manually add a repository entry to their pom.xml or settings.xml.
This repository allows developers to use the CUBRID JDBC driver in Maven or Gradle build environments without any additional repository configuration.

---

## 📦 Maven / Gradle Dependency

### ✅ Maven

``` xml
<dependency>
  <groupId>io.github.srltas</groupId>
  <artifactId>cubrid-jdbc-driver</artifactId>
  <version>11.3.1.0050</version>
</dependency>
```

### ✅ Gradle(Groovy DSL)
``` groovy
implementation 'io.github.srltas:cubrid-jdbc-driver:11.3.1.0050'
```

---

## 📚 Javadoc
- [View API Documentation (javadoc.io)](https://javadoc.io/doc/io.github.srltas/cubrid-jdbc-driver/latest/index.html)

---

## 📄 License
This project repackages the official [CUBRID JDBC Driver](https://github.com/CUBRID/cubrid-jdbc) and distributes it via Maven Central.
The original driver is licensed under the **BSD 3-Clause License**.

Copyright (c) CUBRID Foundation
See the full license in the [LICENSE](./LICENSE) file.

---

## 📂 Repository Structure

```
cubrid-jdbc-driver/
├── src/jdbc/          # Original CUBRID JDBC source
├── pom.xml            # Maven Central-compatible build config
├── README.md
├── LICENSE
└── ...
```

---

## 🤝 Credits
- Original driver maintained by the [CUBRID Foundation](https://www.cubrid.org)

