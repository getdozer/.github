# What is Dozer?

## 📚 Overview

Dozer implements a Real-Time SQL Engine that connects to any of your data sources, transforms and stores the data in an embedded cache powered by LMDB, automatically creates secondary indexes and instantly generates REST and gRPC APIs. Protobuf and Open API documentation are available out of the box. 

Dozer is implemented fully in Rust for fast processing of data and is less resource intensive. 

![dozer](https://user-images.githubusercontent.com/981781/218511427-49be0bea-77b9-480b-bead-218c779c5514.png)


Dozer takes an end-to-end approach, aiming to drastically lower the cost, complexity and effort involved in putting together the infrastructure necessary to build data applications. Today developers have to integrate and maintain a variety of tools to achieve the same result. 


Check out our website and sign up for [Early Access](https:///getdozer.io) to our hosted service.

Checkout our [Documentation](https://getdozer.io/docs/dozer) for more information.

##  What can you do with Dozer

- Create **blazing fast** end to end APIs in minutes with a simple configuration.
- Build and rapidly iterate on customer facing data apps.
- Transform your data in real-time using standard SQL. 
- Cache your data and get search and filter functionality out of the box.
- Extend Dozer with **custom connectors, operators and Api transformations** using **WASM**.
- Built with **Rust** with performance and extensibility in mind.
- OpenAPI documentation and protobuf-based data contracts are auto-generated.

Detailed [Architecture can be found here](https:///getdozer.io/docs/dozer/architecture). 

## Features

**Plug & Play**

Dozer instantly generates fully indexed gRPC and REST APIs automatically. All you need is to configure a YAML file with your data source configuration and the APIs you want to deploy. As simple as that. There is no need to write any additional code saving several developer hours. Dozer is very much customizable. You can refer to your [Contributing](https://getdozer.io/docs/contributing/overview) section for more information on building more connectors as well as transformations. 


**Connect to all sources**

Dozer doesn't make a distinction between types of data sources. Developers can get a seamless experience building products with application databases such as Postgres and MySQL, data warehouses such as SnowFlake and cloud storage such as S3 and Deltalake. Dozer can also consume real-time events and Ethereum data. 

**Combine data from multiple sources**

Dozer can in real-time join data coming from multiple data sources powering advanced use cases such as customer personalization, real-time analytics etc. This can be done using the standard JOIN operator in SQL.

**APIs & Real-time queries**

At the heart of the implementation, Dozer has a streaming data pipeline that works on CDC across all stores. As new data flows in, Dozer incrementally computes aggregations and joins, and offers a far superior query experience than a traditional database for these scenarios. 

Data is stored in a cache built on LMDB (Lightning Memory-Mapped Database) and secondary indexes for single columns are automatically built. This gives users instant queryable APIs with operations such as filter, sort, and order_by functionality. 

**Scaling**

Dozer can be run as a single process for simple applications or can be run in a distributed fashion where writing and reading are de-coupled. This is a cost-effective approach where reading has a very low overhead and can be scaled on demand.


**Authorization**

Dozer offers authorization functionality through JWT tokens. Refer to [API Security](https://getdozer.io/docs/reference/api/security) for more details.

## Comparison
Dozer takes an opinionated and horizontal approach that cuts across different categories. In Dozer, you would find modules and functionalities comparable to streaming databases, caches, search engines and API generation tools.

You can find comparison [documented here](https://getdozer.io/docs/dozer/comparision)


## Releases
We release Dozer typically every 2 weeks and is available on our [releases page](https://github.com/getdozer/dozer/releases/latest). Currently, we publish a binary for Ubuntu 20.04 and also as a docker container.


Please visit our [issues section](https://github.com/getdozer/dozer/issues) if you are having any trouble running the project.


## Contributing
Please refer to [Contributing](https://getdozer.io/docs/contributing/overview) for more details.


## Links
- [Docs](https://getdozer.io/docs/dozer)
- [Quick Start](https://getdozer.io/docs/category/getting-started)
- [Contributing](https://getdozer.io/docs/contributing/overview)
- [Issues](https://github.com/getdozer/dozer/issues)
