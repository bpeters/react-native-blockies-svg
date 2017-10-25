# react-native-blockies-svg
Ethereum blockies for React Native as SVGs. Based on https://github.com/ethereum/blockies

Depends on react-native-svg and needs to be linked.

## Install

```shell
yarn add git+https://github.com/bpeters/react-native-blockies-svg.git

react-native link
```

## General Usage

You can use this provider wherever a Web3 provider is needed, not just in Truffle. For Truffle-specific usage, see next section.

```javascript
import Blockies from 'react-native-blockies-svg';

render() {
    return (
        <Blockies
            size={16}
            scale={8}
            seed="something"
        />
    );
}
```
