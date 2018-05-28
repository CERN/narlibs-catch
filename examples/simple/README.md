# Simple C++ 11 example

## On GNU Linux / Unix

Simply type :
```
../../mvnw compile
```
The unit test in *src/main/cpp* has been compiled into an executable for your operating system.

Then execute the compiled unit test with :
```
find -name catch-simple -type f -exec '{}' '-s' ';'
```

You should see the results of the test.

```
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
catch-simple is a Catch v2.2.2 host application.
Run with -? for options

-------------------------------------------------------------------------------
Factorials are computed
-------------------------------------------------------------------------------
/home/user/workspace/narlibs-catch/examples/simple/src/main/cpp/simple.cpp:8
...............................................................................

/home/user/workspace/narlibs-catch/examples/simple/src/main/cpp/simple.cpp:9: 
PASSED:
  REQUIRE( Factorial(1) == 1 )
with expansion:
  1 == 1

/home/user/workspace/narlibs-catch/examples/simple/src/main/cpp/simple.cpp:10: 
PASSED:
  REQUIRE( Factorial(2) == 2 )
with expansion:
  2 == 2

/home/user/workspace/narlibs-catch/examples/simple/src/main/cpp/simple.cpp:11: 
PASSED:
  REQUIRE( Factorial(3) == 6 )
with expansion:
  6 == 6

/home/user/workspace/narlibs-catch/examples/simple/src/main/cpp/simple.cpp:12: 
PASSED:
  REQUIRE( Factorial(10) == 3628800 )
with expansion:
  3628800 (0x375f00) == 3628800 (0x375f00)

===============================================================================
All tests passed (4 assertions in 1 test case)

```