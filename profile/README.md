# What is Dozer?

## 📚 Overview

Dozer is an open-source platform that allows developers to quickly and easily build, publish, and manage high-performance data APIs. It aims to enhance developer productivity by providing a streamlined process for generating APIs automatically, connecting to a wide range of data sources, and transforming data on the fly.


![Dozer Architecture](https://getdozer.io/img/dozer-binary.svg)

Checkout our [Documentation](https://getdozer.io/docs/dozer) for more information.

### Configurability
Dozer uses a YAML configuration file to define the connectors, sources, endpoints and settings of the API, such as authentication, caching, and security. This configuration file is simple and easy to use, making it easy for developers to understand and modify. Dozer automatically generates the API based on the configuration in both REST and gRPC formats, along with documentation in both OpenAPI and protobuf formats. This streamlined process saves a lot of development time and helps to ensure that the generated APIs are fast, reliable, and easy to use.


### Connectivity
Dozer allows for easy connectivity to several data sources, including traditional databases such as Postgres, Data warehouses such as Snowflake, as well as non-relational sources like blockchain and real-time events. This allows developers to access and combine data to create rich APIs purely through configuration. 



### Performance
Dozer uses a caching layer built on LMDB (Lightning Memory-Mapped Database) to improve performance. LMDB is a high-performance, embedded key-value store that allows for extremely fast data access even when working with large datasets. Additionally, Dozer supports various secondary indexes which further enhance performance.

Dozer implements a real-time streaming SQL layer that can transform data in real-time. Dozer supports commonly used SQL functionalities such as selection, aggregation, joins etc. 


## Features

- **Connect your sources**
    - Import real time data from Postgres as CDC, Snowflake Table Stream etc.
    - Create your own connector using Rust
    - Automatic schema evolution and validation
- **Transform in REAL-TIME**
    - Use SQL to perform joins, aggregations and filter operations in real time across sources.
    - Use it like an ORM; Map relational data to object entities using Dozer SQL extensions
    - Build custom functions for aggregation, selection etc. using WASM
- **Optimize for serving**
    - Define indices with a simple configuration
    - Support for multiple indices such as Inverted, Full Text, Compound, Geo (Coming soon!) etc.
    - Apply filter and sort operations on cached data
    - Support for Push and Pull queries
- **Publish blazing fast APIs**
    - gRPC and REST APIs automatically generated
    - Protobuf an Open API documentation
    - TypeSafe APIs
    - Realtime Streaming


## Links
- [Docs](https://getdozer.io/docs/dozer)
- [Quick Start](https://getdozer.io/docs/category/getting-started)
- [Contributing](https://getdozer.io/docs/contributing/overview)
- [Issues](https://github.com/getdozer/dozer/issues)
