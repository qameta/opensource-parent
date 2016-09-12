# Parent for our Maven projects

[![release-badge][]][release]
[![mavencentral-badge][]][mavencentral]
[![build-badge][]][build]

The parent pom.xml for our Maven projects

To use simple add the following to your pom.xml:

```xml
<parent>
    <groupId>io.qameta</groupId>
    <artifactId>opensource-parent</artifactId>
    <version>$LATEST_VERSION</version>
</parent>
```

[release]: https://github.com/qameta/opensource-parent/releases/latest "Latest release"
[release-badge]: https://img.shields.io/github/release/qameta/opensource-parent.svg?style=flat

[mavencentral]: https://mvnrepository.com/artifact/io.qameta/opensource-parent "Maven central"
[mavencentral-badge]: https://img.shields.io/maven-central/v/io.qameta/opensource-parent.svg?style=flat

[build]: https://ci.qameta.in/job/opensource-parent_deploy/lastBuild "Jenkins build"
[build-badge]: https://ci.qameta.in/buildStatus/icon?job=opensource-parent_deploy