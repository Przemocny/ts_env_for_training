# Boilerplate starter for simple Typescript tasks (with testing by jest) by Localhost Academy

by [Localhost Academy](https://academy.localhost-group.com/)


#### boilerplate includes:
- typescript for better code writting
- jest with typescript for comfortable testing
- nodemon for real time script reload 


## how to install global deps (if you don't already have them):
```javascript
npm install -g typescript nodemon jest ts-jest esbuild npx
// or 
yarn global add typescript nodemon jest ts-jest esbuild npx
```


## how to install deps:
```javascript
npm install 
// or 
yarn
```

## boilerplate structure:
```javascript
// src/* - developers files
// build/* - production files

// src/common/*.ts - parts shared in script like utils or helpers
// src/common/__test__/*.test.ts - example of test for shared part
// src/task/*.ts - main part of script
// src/data/*.json - hardcoded data dir
// src/typings/index.d.ts - custom shared types
```

## how to start developing:
```javascript
npm run start
// or 
yarn start
```

## how to start testing:
```javascript
npm run test
// or 
yarn test
```
