---
id: get-started
title: Get Started
---

Install the library code as a regular npm package:

```bash
npm install -save solidity-treemap
```

You can then import the `TreeMap.sol` like so:

```solidity
import "solidity-treemap/contracts/TreeMap.sol";

contract TreeMapMock {
  using TreeMap for TreeMap.Map;

  TreeMap.Map sortedMap1;
  TreeMap.Map sortedMap2;
  ...
}
```
