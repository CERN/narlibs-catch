# Maven NAR packaging for Catch
Platform-independent (noarch) NAR packaging for Catch.

Catch stands for C++ Automated Test Cases in a Header and is a multi-paradigm test framework for C++.

As opposed to other testing frameworks, Catch is a header-only library, making it perfect to embed into your favourite NAR packages.

* More info about Catch at https://github.com/catchorg/Catch2.
* More info about the Maven NAR plugin at http://maven-nar.github.io/


# How to use


Simply add the dependency to your Maven NAR like so :

```xml
<dependency>
  <groupId>com.github.cern.narlibs</groupId>
  <artifactId>catch</arifactId>
  <version>[2.2.2,)</version>
  <type>nar</type>
</dependency>
```

Note that Catch v2+ requires C++ 11  (e.g. for GCC you need the option -std=c++11).

For working examples, please consult https://github.com/CERN/narlibs-catch/tree/master/examples/


