oGLOWo Maven Repo
================

Public libraries that I need and don't have the latest and greatest at Maven Central

------------------------
Howto

Put this in your pom.xml

```xml
<repositories>
    <repository>
        <id>oglowo-maven-repo-releases</id>
        <url>https://github.com/oglowo/oglowo-maven-repo/raw/master/releases</url>
    </repository>
</repositories>
```

Libraries included
------------------
Netflix Astyanax - earliest version in this repo is 1.56.13

Insert this into your pom.xml in the dependencies section

```
<dependency>
    <groupId>com.netflix.astyanax</groupId>
    <artifactId>astyanax</artifactId>
    <version>1.56.13</version>
    <scope>provided</scope>
</dependency>
```

