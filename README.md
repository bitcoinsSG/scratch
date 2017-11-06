<p align="center">
  <img width="445" height="445" src="manuscript/resources/images/logo.png">
</p>

# access genesis contract | access network | core 
> a purely democratic, user centric, cryptocurrency network for developing economies

<pre>
  <p align="center" style="bold">❚ <a href="https://github.com/ACXNetwork/acx-genesis-core">access genesis contract</a> ❚ ════ ❚ <a href="https://github.com/ACXNetwork/acx-voting-core">access voting contract</a> ❚</p>
</pre>
this repository forms a coupling with [access voting contract](https://github.com/ACXNetwork/acx-voting-core "access voting contract") that collectively comprise of the core code base for the access network


## technology
| software      | version       | purpose  |
| ------------- |:-------------:| -----:|
| [ethereum](https://github.com/ethereum "ethereum")    | => 0.8.0 | prod |
| [solidity](https://github.com/ethereum/solidity "solidity") | => 0.4.2 | dev, prod |
| [nodejs](https://github.com/nodejs "nodejs")    | => 6.9.2 | dev |
| [truffle](https://github.com/trufflesuite/truffle "truffle")    | => 4.0.1    | dev, prod |
| [zeppelin-solidity](https://github.com/OpenZeppelin/zeppelin-solidity "zeppelin-solidity")    | =>  1.3.0    | dev |


## main concepts

| file        | puropse           | Cool  |
| :------------- |:-------------| -----:|
| accessCoin.sol      | core coin logic extending ERC20 functionality | $1600 |
| tokenLaunchSale.sol     | logic for token launch/sale for bootstrapping network     |   $12 |
| deployACX.sol | logic for initialization and deployment of code to testnet or mainnet | |


## development

```shell
commands here
```

Here you should say what actually happens when you execute the code above.
### built with
List main libraries, frameworks used including versions (React, Angular etc...)

### prerequisites and installation

```shell
git clone https://github.com/ACXNetwork/acx-genesis-core.git
npm install -g truffle
cd acx-genesis-core
npm install --save zeppelin-solidity

```

### setting up dev

Here's a brief intro about what a developer must do in order to start developing
the project further:

```shell
git clone https://github.com/your/your-project.git
cd your-project/
packagemanager install
```

And state what happens step-by-step. If there is any virtual environment, local server or database feeder needed, explain here.

### building

If your project needs some additional steps for the developer to build the
project after some code changes, state them here. for example:

```shell
./configure
make
make install
```

Here again you should state what actually happens when the code above gets
executed.

### deployment
give instructions on how to build and release a new version
In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```shell
packagemanager deploy your-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

## versioning

We can maybe use [SemVer](http://semver.org/) for versioning. For the versions available, see the [link to tags on this repository](/tags).


## configuration

Here you should write what are all of the configurations a user can enter when
using the project.

## testing

Describe and show how to run the tests with code examples.
Explain what these tests test and why.

```shell
Give an example
```

## style guide

Explain your code style and show how to check it.

## licensing

standard MIT license
