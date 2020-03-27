# Design patterns implemented for Blockchain applications

**Owner:  [Varun Ojha](https://github.ibm.com/varun-ojha)**

[![Build Status](https://travis.ibm.com/BlockchainAB/BlockchainDevelopmentDesignPatterns.svg?token=sQbGqm1RNTX4ZceCsxf9&branch=master)](https://travis.ibm.com/BlockchainAB/BlockchainDevelopmentDesignPatterns)


# Design patterns for Blockchain based application development
The purpose of this repository is to document design patterns and development best practices when developing end to end applications using Blockchain.
To start with I would be adding approaches, architecture and code snippets for the following design patterns. Please feel free to reach out to me for collaboration on any of the patterns. If you have some specific problems/patterns in mind that you do not see on the list please reach out and I would be happy to add them.

- Interactive UI design for Blockchain based applications
- Asynchronous API design for Blockchain based applications
- Secure sync and off chain query pattern for Blockchain based applications
- Chaincode and client side application development for Blockchain Multi version concurrency control
- Attribute based Access control
- Higher throughput and latency with Batching


# Introduction

Design patterns are the best formalized practices a programmer can use to
solve common problems when designing an application or system.

Design patterns can speed up the development process by providing tested, proven
development paradigms.

Reusing design patterns help prevent subtle issues which cause major
problems, and it also improves code readability for coders and architects who
are familiar with the patterns.

# Getting started

Before you dive into the material, you should be familiar with various
Programming/Software Design Principles.

All designs should be as simple as possible. You should start with KISS, YAGNI,
and Do The Simplest Thing That Could Possibly Work principles. Complexity and
patterns should only be introduced when they are needed for practical
extensibility.

Once you are familiar with these concepts you can start drilling down into
patterns by any of the following approaches

 - Using difficulty tags, `Difficulty-Beginner`, `Difficulty-Intermediate` & `Difficulty-Expert`.
 - Using pattern categories, `UI`, `Front-end` and others.
 - Search for a specific pattern. Can't find one? Please report a new pattern [here](xxxxx).


 ## Blockchain Patterns

| Pattern | Description | Status |
|:-------:|:----------- |:------:|
| [NonBlockingUIPattern](./docs/design_patterns/UIResponsivenessPattern.md) | Provides design and architecture for creating an interactive  and non blocking Blockchain application UI| ✔ |
| [AsyncPattern](./docs/design_patterns/AsyncPattern.md) | Discusses the API design and the interaction with other components such as off chain store and the events service | ✔ |
| [SecureSyncPattern](./docs/design_patterns/SecureSyncPattern.md) | It covers the design of the event service that can be used to securely sync Blockchain with an application’s off chain store | ✔ |
| [D-pattern](./docs/design_patterns/xx.md) |  xxxxx  | ✔ |



# How to contribute

If you are willing to contribute to the project you will find the relevant information in our [developer wiki](https://github.com/BlockchainAB/BlockchainDevelopmentDesignPatterns/wiki). We will help you and answer your questions in the [Slack Channel](slackchannel).

## License
This code pattern is licensed under the Apache Software License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
 