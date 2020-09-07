# SYNOPSIS

[![NPM Package](https://img.shields.io/npm/v/rlp.svg)](https://www.npmjs.org/package/rlp)
[Recursive Length](https://github.com/ethereum/wiki/wiki/RLP) Prefix Encoding for node.js.

## USAGE

```javascript
import {
  decode,
  encode,
} from "https://deno.land/x/npm_rlp@2.2.6/mod.ts";
import {assertEquals} from "https://deno.land/std@0.68.0/testing/asserts.ts";

const nestedList = [[], [[]], [[], [[]]]];
const encoded = encode(nestedList);
const decoded = decode(encoded);
assertEquals(nestedList, decoded);
```

## Tests

The tests require `--allow-read` in order to read the rlp official json test suite

# EthereumJS

See our organizational [documentation](https://ethereumjs.readthedocs.io) for an introduction to `EthereumJS` as well as information on current standards and best practices.

If you want to join for work or do improvements on the libraries have a look at our [contribution guidelines](https://ethereumjs.readthedocs.io/en/latest/contributing.html).
