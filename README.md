
Samples running on local Blockchain.

Download Skunkworks sample contracts Truffle setup.
https://github.com/ARKeth/skunkworks


Gets the value function
SimpleStorage.deployed().then(function(instance){return instance.get.call();}).then(function(value){return value.toNumber()});

Sets the new Value 
SimpleStorage.deployed().then(function(instance){return instance.set(4);});
ONE CLICK BLOCKCHAIN
Quickly fire up a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates.

Blockchain viewer
http://truffleframework.com/ganache/