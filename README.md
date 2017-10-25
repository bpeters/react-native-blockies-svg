# react-native-blockies-svg
Ethereum blockies for React Native as SVGs. Based on https://github.com/ethereum/blockies

Depends on react-native-svg and needs to be linked.

## Install

```shell
yarn add git+https://github.com/bpeters/react-native-blockies-svg.git

react-native link
```

## General Usage

Treat like any other react component, included props: size, scale, seed, color, bgcolor, and spotcolor.

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
