# TACT jetton demo

Please add .env file in root dir and add MNEMONICS=XXXX(your wallet mnemonics).

![Jetton demo logo](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAAb1BMVEX////4+Pi3ubtvcnZNUVU+Q0cpLjLr6+x3en0sMTYkKS59gIORk5aUl5n8/Pzw8PFTV1tbX2Pc3d5DSEzn5+g3PECLjpFKTlKFh4qxs7XCxMUwNTq/wcLh4uPV1tZzd3o/Q0jOz9CmqKpjZ2qfoaSrd37mAAABPUlEQVR4AW3TBZKEMBAF0B8GCHzcnbW5/xm30qEyknklcU/DgQpuYRTHUXgLFHw6SemkmcYrlcd8kRYlnlQ1PU0Fp434Qde75Qd+1FUQKiRZjyGfTGNjKhWMmSQXYO3Ibao3MlqBnSRzADhk/ycAdcqclSSHnEUD+KLt8KalMQMqpl3izU5jKxHQGCq8Ud80fq4VfuFZaIyQO4wVPEre5g+RrIAPJrkQSL8OPjv3htQmH8guU5uwgseeP7ITMYBnpdFgvlJPcx0zoLjjzS/FDrVRvH6xsqDYlLx29huRUaFx6YuI1mhKMbddf9trEzca7rmRk/FxpiRXiJO8FDBURyb4yfO7glC8TOpacmAc4ElMEWlc2oGckjwvYVFEB5wjouE6uLBwquypQym/scKrM4njElYaJy182q15aDj/oQMZkS8JH3IAAAAASUVORK5CYII=)

This project has ready to use TACT compiler, typescript + jest with ton-contract-executor, example how to do tests.
To run deployment of `jetton.tact` example on testnet, you need input your deployment wallet seed [here](https://github.com/Reveloper/tact-jetton/blob/main/sources/jetton.deploy.ts#L20) and owner address [here](https://github.com/Reveloper/tact-jetton/blob/main/sources/jetton.deploy.ts#L46).
Note, that in deployment script is using walletV4. If you want to use your V3R2, you need change wallet contract [here](https://github.com/Reveloper/tact-jetton/blob/main/sources/jetton.deploy.ts#L31).

```bash
yarn test # To test contract
yarn build # To build contract
yarn deploy # To deploy contract (need input deployment wallet)
```

## Licence

MIT
