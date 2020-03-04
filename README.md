# XML Schema JAXB 

This project demonstrates **jaxb2-maven-plugin** to generate Java Beans from multiple xml schema file.  It uses
**threeten-jaxb-core** to convert xsd:date, xsd:time, xsd:datetime to Java8 LocalDate, LocalTime and ZonedDateTime. The generated jar can be used for conversions between Java Bean and XML

## Usage

```bash
mvn jaxb2:xjc
mvn package
```

**Tip**:
* the xsd must be in src/main/xsd directory
* it is better to have one schema -> one jar to avoid conflict 