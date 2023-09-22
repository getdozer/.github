<div align="center">
    <a target="_blank" href="https://getdozer.io/">
        <br><img src="https://dozer-assets.s3.ap-southeast-1.amazonaws.com/logo-blue.svg" width=40%><br>
    </a>
</div>

<p align="center">
  <a href="https://github.com/getdozer/dozer/actions/workflows/dozer.yaml" target="_blank"><img src="https://github.com/getdozer/dozer/actions/workflows/dozer.yaml/badge.svg" alt="CI"></a>
  <a href="https://coveralls.io/github/getdozer/dozer?branch=main" target="_blank"><img src="https://coveralls.io/repos/github/getdozer/dozer/badge.svg?branch=main&t=kZMYaV&style=flat" alt="Coverage Status"></a>
  <a href="https://getdozer.io/docs/dozer" target="_blank"><img src="https://img.shields.io/badge/doc-reference-green" alt="Docs"></a>
  <a href="https://discord.com/invite/3eWXBgJaEQ" target="_blank"><img src="https://img.shields.io/badge/join-on%20discord-primary" alt="Join on Discord"></a>
  <a href="https://github.com/getdozer/dozer/blob/main/LICENSE.txt" target="_blank"><img src="https://img.shields.io/badge/license-Apache-blue" alt="License"></a>
</p>

## Overview

Dozer is a **data platform for building, deploying and maintaining real-time data products.**

It is ideal for companies with multiple databases, data warehouses and data lakes that are in need of combining, aggregating and transforming data in real time, and create customer facing or internal data applications. 

*Put it simply, Dozer empowers a single developer go from data sources to ready-made APIs in just a few minutes. All with just a with a simple configuration file.*

## How it works
Dozer pulls data from various sources like databases, data lakes, and data warehouses using Change Data Capture (CDC) and periodic polling mechanisms. This ensures up-to-date data ingestion in real-time or near-real-time.

After capturing data, Dozer offers the possibility of combining, transforming and aggregating it 
using its own internal real-time transformation engine. It supports Streaming SQL, WebAssembly (coming soon) and TypeScript (coming soon), as well as ONNX for performing AI predictions in real-time. 

After processing, data is stored and indexed in a low-latency datastore (based on [LMDB](https://github.com/LMDB/lmdb)), queryable using REST and gRPC.


## Repos
Please find further instructions in the following repos. 

Dozer core - [getdozer/dozer](https://github.com/getdozer/dozer)

Dozer Samples  - [getdozer/dozer-samples](https://github.com/getdozer/dozer-samples)

Dozer JS libraries (JS, React, Vue etc) -[getdozer/dozer-js](https://github.com/getdozer/dozer-js)


Dozer Python - [getdozer/dozer-python](https://github.com/getdozer/dozer-python)

## Links
[Docs](https://getdozer.io/docs/dozer)

[Getting started](https://getdozer.io/docs/getting_started)


