# Spring Batch Toolkit #

This toolkit provides additional features to Spring Batch.

## Features ##

* Tasklet used to delete data from Spring Batch Metadata tables that are N months old.


## Quick Start ##

Download the jar though Maven:
```xml
<dependency>
  <groupId>com.javaetmoi.core</groupId>
  <artifactId>spring-batch-toolkit</artifactId>
  <version>0.1</version>
</dependency> 
       
<repository>
  <id>javaetmoi-maven-release</id>
  <releases>
    <enabled>true</enabled>
  </releases>
  <name>Java & Moi Maven RELEASE Repository</name>
  <url>http://repository-javaetmoi.forge.cloudbees.com/release/</url>
</repository>
```

```xml

<repository>

</repository>
```

## Contributing to Spring Batch Tookit ##

* Github is for social coding platform: if you want to write code, we encourage contributions through pull requests from [forks of this repository](http://help.github.com/forking/). If you want to contribute code this way, please reference a GitHub ticket as well covering the specific issue you are addressing.

### Development environment installation ###

Download the code with git:
git clone git://github.com/arey/spring-batch-toolkit.git

Compile the code with maven:
mvn clean install

If you're using an IDE that supports Maven-based projects (InteliJ Idea, Netbeans or m2Eclipse), you can import the project directly from its POM. 
Otherwise, generate IDE metadata with the related IDE maven plugin:
mvn eclipse:clean eclipse:eclipse

## Documentation ##

French articles on the [javaetmoi.com](http://javaetmoi.com) blog:
* [Parallélisation de traitements batchs](http://javaetmoi.com/2012/12/parallelisation-de-traitements-batchs/)
* [Spring Batch s’auto-nettoie](http://javaetmoi.com/2012/06/sprint-batch-sauto-nettoie/)

## Credits ##

* Uses [Maven](http://maven.apache.org/) as a build tool
* Uses [Cloudbees](http://www.cloudbees.com/foss) for continuous integration builds whenever code is pushed into GitHub