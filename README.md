# Micronaut service utilities

[![Build Status](https://travis-ci.com/qbicsoftware/micronaut-utils-lib.svg?branch=development)](https://travis-ci.com/qbicsoftware/micronaut-utils-lib)[![codecov](https://codecov.io/gh/qbicsoftware/micronaut-utils-lib/branch/master/graph/badge.svg)](https://codecov.io/gh/qbicsoftware/micronaut-utils-lib)

micronaut-utils-lib, version 1.0.0-SNAPSHOT - _Encapsulation of third party classes that need to be used in the QBiC service environment, using Micronaut ([micronaut.io](https://micronaut.io))_.

## Author
Created by Sven Fillinger (sven.fillinger@qbic.uni-tuebingen.de).

## Description

A small collection of classes, that are shared between projects that make use of the Micronaut framework.

## How to Install

### Add QBiC's Maven repository

Make sure to configure Maven such that it searches in the [QBiC repos](https://qbic-repo.am10.uni-tuebingen.de/#browse/browse:maven-snapshots) as well:

```
<repositories>
  ...
  <repository>
    <releases>
      <enabled>false</enabled>
    </releases>
    <snapshots>
      <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
      <checksumPolicy>fail</checksumPolicy>
    </snapshots>
    <id>nexus-snapshots</id>
    <name>QBiC Snapshots</name>
    <url>https://qbic-repo.am10.uni-tuebingen.de/repository/maven-snapshots</url>
  </repository>
  <repository>
    <releases>
      <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
      <checksumPolicy>fail</checksumPolicy>
    </releases>
    <snapshots>
      <enabled>false</enabled>
    </snapshots>
    <id>nexus-releases</id>
    <name>QBiC Releases</name>
    <url>https://qbic-repo.am10.uni-tuebingen.de/repository/maven-releases</url>
    </repository>
</repositories>
```

### Add Maven dependency in your `pom.xml`

Add the library to your dependencies in the project's `pom.xml`:

```
<dependency>
  <groupId>life.qbic</groupId>
  <artifactId>micronaut-utils-lib</artifactId>
  <version>1.0.0-SNAPSHOT</version>
</dependency>
```




