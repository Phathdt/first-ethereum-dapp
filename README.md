first eth app

install
```
yarn global add npx
yarn install
```

compile
```
solc --bin --abi -o ./build FirstContract.sol
```


run

```
npx ganache-cli
```

in another terminal

run
```
node deploy.js
```

copy hex number and paste to `myContractAddress` in html.index
copy content in build/FirstContract.abi to `myAbi`

run
```
npx http-server
```
