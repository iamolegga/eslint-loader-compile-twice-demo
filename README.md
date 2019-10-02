# ESLINT LOADER COMPILE TWICE DEMO

```sh
git clone https://github.com/iamolegga/eslint-loader-compile-twice-demo.git
cd eslint-loader-compile-twice-demo
npm i
npm run start
```

1. when webpack started clear console (cmd + K)
2. open `src/index.js`
3. remove quotes from object property and save

console shows two compilations:

```sh

Compilation  starting…


Compilation  finished

Hash: 90a67c6e23dc77a6f06b
Version: webpack 4.41.0
Time: 35ms
Built at: 10/02/2019 5:49:20 PM
    Asset     Size  Chunks             Chunk Names
bundle.js  4.2 KiB    main  [emitted]  main
Entrypoint main = bundle.js
[./src/index.js] 55 bytes {main} [built]

Compilation  starting…


Compilation  finished

Hash: 92ff8cde8bef5080692c
Version: webpack 4.41.0
Time: 11ms
Built at: 10/02/2019 5:49:21 PM
    Asset      Size  Chunks             Chunk Names
bundle.js  4.21 KiB    main  [emitted]  main
Entrypoint main = bundle.js
[./src/index.js] 57 bytes {main} [built]

```