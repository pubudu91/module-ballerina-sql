Ballerina SQL library
===================

  [![Build](https://github.com/ballerina-platform/module-ballerina-sql/workflows/Build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-sql/actions?query=workflow%3ABuild)
  [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerina-sql.svg)](https://central.ballerina.io/ballerina/sql)
  [![GitHub Release Date](https://img.shields.io/github/release-date/ballerina-platform/module-ballerina-sql.svg)](https://central.ballerina.io/ballerina/sql)
  [![GitHub Open Issues](https://img.shields.io/github/issues-raw/ballerina-platform/module-ballerina-sql.svg)](https://github.com/ballerina-platform/module-ballerina-sql/issues)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-sql.svg)](https://github.com/ballerina-platform/module-ballerina-sql/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

SQL package for <a target="_blank" href="https://ballerina.io/">Ballerina</a> language.

For more information on all the operations supported by the `sql:Client`, which includes the below mentioned operations, see [API Docs](https://ballerina.io/swan-lake/learn/api-docs/ballerina/sql/).

1. Connection Pooling
1. Querying data
1. Inserting data
1. Updating data
1. Deleting data
1. Batch insert and update data
1. Execute stored procedures
1. Closing client

For a quick sample on demonstrating the usage see [Ballerina By Example](https://ballerina.io/swan-lake/learn/by-example/)

## Building from the source

1. To build the JDBC library use, issue the following command.
        
        ./gradlew clean build

2. To run the integration tests

        ./gradlew clean test

3. To build the module without tests,

        ./gradlew clean build -x test

4. To debug the tests,

        ./gradlew clean build -Pdebug=<port>

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. To start contributing, read these [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md) for information on how you should go about contributing to our project.

Check the issue tracker for open issues that interest you. We look forward to receiving your contributions.

## Useful links

* The ballerina-dev@googlegroups.com mailing list is for discussing code changes to the Ballerina project.
* Chat live with us on our [Slack channel](https://ballerina.io/community/slack/).
* Technical questions should be posted on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
* Ballerina performance test results are available [here](performance/benchmarks/summary.md).
