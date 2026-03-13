## Overview

The PostgreSQL driver provides a reliable and high-performance connectivity to PostgreSQL databases. It enables efficient execution of SQL queries, updates, and other database operations. The driver is designed to provide a seamless experience for interacting with PostgreSQL, supporting various data types and advanced features of the database.

### Key Features

- High-performance and reliable database connectivity
- Support for various SQL operations (Query, Execute, Batch)
- Efficient handling of database connections and resources
- Support for database-specific data types and features
- Secure communication with TLS and authentication
- GraalVM compatible for native image builds

## Package overview

This Package bundles the latest PostgreSQL drivers so that the PostgreSQL connector can be used in ballerina projects easily.

## Compatibility

| |     Version      |
|:---|:----------------:|
|Ballerina Language |   **2201.7.0**   |
|PostgreSQL Driver |    **42.6.0**    |
|PostgreSQL DB Server| **8.4 or above** |

> The above PostgreSQL drivers are released under the [BSD 2-Clause](https://jdbc.postgresql.org/about/license.html).

## Usage

To add the PostgreSQL driver dependency the project, simply import the module as below,

```ballerina
import ballerina/sql;
import ballerinax/postgresql;
import ballerinax/postgresql.driver as _;
```

# Useful Links
* Chat live with us via our [Discord server](https://discord.gg/ballerinalang).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
