# Maven NAR packaging for Catch2
Platform-independent (noarch) NAR packaging for Catch2.

Catch stands for C++ Automated Test Cases in a Header and is a multi-paradigm test framework for C++.

As opposed to other testing frameworks, Catch is a header-only library, making it perfect to embed into your favourite NAR packages.

* More info about Catch at https://github.com/catchorg/Catch2.
* More info about the Maven NAR plugin at http://maven-nar.github.io/


# How to use

*WARNING* this library is not yet deployed on Maven Central, if you want to use it, you have to git clone and mvn install it.

Simply add the dependency to your Maven NAR like so :

```xml
<dependency>
  <groupId>com.github.cern</groupId>
  <artifactId>narlibs-catch</arifactId>
  <type>nar</type>
</dependency>
```
