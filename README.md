# secp256k1-node_fast_unsafe

Minor edits to make this work with secp256k1_fast_unsafe(https://github.com/llamasoft/secp256k1_fast_unsafe). 
This is really only for use with 21e8Miner, if you want to use it for something else figure it out on your own.


This module provides native bindings to [bitcoin-core/secp256k1](https://github.com/bitcoin-core/secp256k1). In browser [elliptic](https://github.com/indutny/elliptic) will be used as fallback.

Works on node version 10.0.0 or greater, because use [N-API](https://nodejs.org/api/n-api.html).


## Installation

```
git clone https://github.com/ivmidable/secp256k1-node_fast_unsafe
cd secp256k1-node_fast_unsafe
npm install -g node-gyp  (if you don't have node-gyp installed)
node-gyp configure
node-gyp build
npm install
```

## LICENSE

This library is free and open-source software released under the MIT license.
