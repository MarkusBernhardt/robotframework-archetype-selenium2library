robotframework-archetype-selenium2library
=========================================

Robot Framework archetype for creating a testsuite using the Selenium2Library.

Note that an existing installation of *Oracle JDK 7* and *Apache Maven 3*
are required to use this archetype.

Usage
-----

```bash
$ mvn -B archetype:generate \
      -DarchetypeGroupId=com.github.markusbernhardt \
      -DarchetypeArtifactId=robotframework-archetype-selenium2library \
      -DarchetypeVersion=1.0.0 \
      -DgroupId=com.yourcompany.yourdepartment \
      -DartifactId=yourproject-yourtestsuite

$ cd yourproject-yourtestsuite

$ mvn test

[INFO]
[INFO] --- robotframework-maven-plugin:1.2:run (test) @ yourproject-yourtestsuite ---
==============================================================================
Robotframework
==============================================================================
Robotframework.Testsuites
==============================================================================
Robotframework.Testsuites.Google
==============================================================================
Open And Close Google Site                                            | PASS |
------------------------------------------------------------------------------
Search Robotframework Selenium2Library                                | PASS |
------------------------------------------------------------------------------
Search With JavaScript Locator                                        | PASS |
------------------------------------------------------------------------------
Search With JavaScript Locator And Delimiter                          | PASS |
------------------------------------------------------------------------------
Search With JavaScript Locator Text                                   | PASS |
------------------------------------------------------------------------------
Search Without Locator Type                                           | PASS |
------------------------------------------------------------------------------
Get Id Of Active Element With JavaScript                              | PASS |
------------------------------------------------------------------------------
Robotframework.Testsuites.Google                                      | PASS |
7 critical tests, 7 passed, 0 failed
7 tests total, 7 passed, 0 failed
==============================================================================
Robotframework.Testsuites                                             | PASS |
7 critical tests, 7 passed, 0 failed
7 tests total, 7 passed, 0 failed
==============================================================================
Robotframework                                                        | PASS |
7 critical tests, 7 passed, 0 failed
7 tests total, 7 passed, 0 failed
==============================================================================
Output:  /yourproject-yourtestsuite/target/robotframework-reports/output.xml
XUnit:   /yourproject-yourtestsuite/target/robotframework-reports/TEST-robotframework.xml
Log:     /yourproject-yourtestsuite/target/robotframework-reports/log.html
Report:  /yourproject-yourtestsuite/target/robotframework-reports/report.html
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------

```