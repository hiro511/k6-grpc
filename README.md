## I did ...

```install bash
cd grpc-node/packages/grpc-js-core/
npm install
npm install http2
tsc -t ES6 --sourceMap false
browserify build/src/index.js -s build/src/index > grpc.js
cd ../../..
k6 run script.js
```

Then, the following error occurs.
```error bash


```