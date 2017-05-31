# eth-contract-api
[![CircleCI](https://circleci.com/gh/adridadou/eth-contract-api/tree/develop.svg?style=svg)](https://circleci.com/gh/adridadou/eth-contract-api/tree/develop)
[![Coverage Status](https://coveralls.io/repos/github/adridadou/eth-contract-api/badge.svg?branch=develop)](https://coveralls.io/github/adridadou/eth-contract-api?branch=develop)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3b1efe2be2094d8587e5dc22b8d4a00b)](https://www.codacy.com/app/Adridadou/eth-contract-api?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=adridadou/eth-contract-api&amp;utm_campaign=Badge_Grade)
[![Gitter](https://badges.gitter.im/eth-contract-api/Lobby.svg)](https://gitter.im/eth-contract-api/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Web3J api wrapper to use rpc ethereum nodes with ease through the standardised `EthereumFaçade` interface

#Getting started
Here is a quick guide on how to install and use this library
##Installation
You can find the application in its bintray repo.
To add the repository, add the following to your pom.xml
````
     <repository>
        <id>bintray</id>
        <url>https://dl.bintray.com/cubefriendly/maven/</url>
    </repository>
````

Then you are ready to add eth-propeller-web3j as a dependency
````
<dependency>
    <groupId>org.adridadou</groupId>
    <artifactId>eth-propeller-web3j</artifactId>
    <version>[put the latest version here]</version>
</dependency>
````

##Setup
Now that you have added the library as a dependency, it is time to use it.



