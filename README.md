# pekko-libraries-bom

Bill of Materials (BOMs) for the Apache Pekko libraries.

```
<dependencyManagement>
  <dependencies>
    <dependency>
        <groupId>com.github.pjfanning</groupId>
        <artifactId>pekko1.1-libraries-bom_2.13</artifactId>
        <version>2025.5.0</version>
        <type>pom</type>
        <scope>import</scope>
    </dependency>
  </dependencies>
</dependencyManagement>
```

`pekko1.1-libraries-bom_2.12` and `pekko1.1-libraries-bom_3` are also supported. The suffix is the Scala Binary version.

The `1.1` part of the name reflects that the Pekko 1.1 libs are out.
The `2025.5.0` versioning is based on the year and the month while the `patch part` of the version will increment if we need patch changes.

There are also `pekko1.0-libraries-bom` files if you want to stick with Pekko 1.0.

The aim is to support all of the libs published by Apache Pekko team.
* pekko core libs - see pekko-bom ([example](https://repo1.maven.org/maven2/org/apache/pekko/pekko-bom_2.13/1.0.2/pekko-bom_2.13-1.0.2.pom))
* pekko-http libs - see pekko-http-bom ([example](https://repo1.maven.org/maven2/org/apache/pekko/pekko-http-bom_2.13/1.0.0/pekko-http-bom_2.13-1.0.0.pom))
* [Other Pekko Modules](https://pekko.apache.org/modules.html)

## sbt

sbt build tools users need to use an sbt plugin to use BOMs - see https://github.com/heremaps/here-sbt-bom

I haven't used this myself. So far, the BOMs have only been tested using Apache Maven and Gradle builds.
