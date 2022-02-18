# install to have the same repo :


```shell
npm init -y
yarn add --dev hardhat
yarn add --dev "hardhat@^2.8.4" "@nomiclabs/hardhat-waffle@^2.0.0" "ethereum-waffle@^3.0.0" "chai@^4.2.0" "@nomiclabs/hardhat-ethers@^2.0.0" "ethers@^5.0.0"
yarn add --dev ts-node typescript
yarn add --dev chai @types/node @types/mocha @types/chai
npx hardhat
```

Then :
- replace hardhat.config.js, sample-test.js and sample-script.js by theses in
./Update_files/ directory.
- create a tsconfig.json file, content is in ./Update_files/ directory.

Should move package.json too, scripts inside.  