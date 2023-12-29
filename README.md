# pekko-libraries-bom

A partial BOM has been published to Sonatype OSS snapshot repository.

```
    <dependency>
        <groupId>com.github.pjfanning</groupId>
        <artifactId>pekko1.0-libraries-bom_2.13</artifactId>
        <version>2024.1.1-SNAPSHOT</version>
        <type>pom</type>
        <scope>import</scope>
    </dependency>
```

`pekko1.0-libraries-bom_2.12` and `pekko1.0-libraries-bom_3` are also supported.

The `1.0` part of the name reflects that Pekko 1.0 libs are out but soon we will start seeing 1.1 era libs. The `2.13` suffix is the Scala binary version.
The `2024.1.1` versioning is based on the year and the month while the `patch part` of the version will increment if we need patch changes.

The aim is to support all the libs published by Apache Pekko team but so far, the only ones supported are
* pekko core libs - see pekko-bom ([example](https://repo1.maven.org/maven2/org/apache/pekko/pekko-bom_2.13/1.0.2/pekko-bom_2.13-1.0.2.pom))
* pekko-http libs - see pekko-http-bom
* some pekko-managment libs
* some pekko-grpc libs
* some pekko-connectors-kafka libs

