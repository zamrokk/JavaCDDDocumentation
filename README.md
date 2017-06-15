# JavaCDD Documentation
The documentation for JavaCDD tutorial

This tutorial helps you understand how to set a blockchain network locally based on Hyperledger Fabric V0.6, create a simple smart contract in Java and interact with it using the HTTP API and the SDK.

The project is split into different sub projects listed here on section [References](#References)

An introduction to Bluemix Blockchain as a Service is part of this tutorial promoting the IBM infrastructure to host the network in Production. Remember that blockchain is a distributed system of several nodes, each one can consume potential high resources depending of the distributed applications you deploy on the network. For a tutorial is more suitable to run it on a development mode locally as we don't need such resources.

## Flow

![Flow](images/architecture.png =100%)

## Included Components
- [Hyperledger Fabric](https://www.hyperledger.org/)
- [Hyperledger Fabric Java SDK](https://github.com/hyperledger/fabric-sdk-java)
- [Spring Boot](https://projects.spring.io/spring-boot/)
- [Bluemix](https://console.ng.bluemix.net/)
- [Docker](https://www.docker.com)

## References
* [JavaCDD](https://github.com/WASdev/sample.microservicebuilder.docs) : the chaincode java project
* [JavaCDDNetwork]() : the scripts to create / destroy the blockchain network locally 
* [JavaCDDWeb](): the client web application using the JavaSDK and exposing an API

# License
[Apache 2.0](LICENSE)
