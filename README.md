# QATools Open source parent

[![release](http://github-release-version.herokuapp.com/github/qatools/opensource-parent/release.svg?style=flat)](https://github.com/qatools/opensource-parent/releases/latest)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/ru.qatools/opensource-parent/badge.svg?style=flat)](https://maven-badges.herokuapp.com/maven-central/ru.qatools/opensource-parent)
[![build](https://img.shields.io/jenkins/s/http/ci.qatools.ru/opensource-parent_master-deploy.svg?style=flat)](http://ci.qatools.ru/job/opensource-parent_master-deploy/lastBuild/)

The parent pom.xml for our open source projects

To use simple add the following to your pom.xml:

```xml
<parent>
    <groupId>ru.qatools</groupId>
    <artifactId>opensource-parent</artifactId>
    <version>$LATEST_VERSION</version>
</parent>
```