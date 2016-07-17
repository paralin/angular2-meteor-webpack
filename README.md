Meteor Angular2 Webpack
=======================

Attempts to get angular2 + meteor + webpack working.

This commit version has:

 - Follow webpack:webpack getting started

It has the following showstopper errors:

```
[[[[[ ~/Documents/angular2-webpack ]]]]]

=> Started proxy.
=> Started MongoDB.
webpack built 1bc60b9fd1d1c0d04167 in 104ms  \
Hash: 1bc60b9fd1d1c0d04167
Version: webpack 1.13.0
Time: 104ms
 Asset     Size  Chunks       Chunk Names
web.js  22.9 kB       0       main
chunk    {0} web.js (main) 61 bytes [rendered]
    [0] multi main 40 bytes {0} [built] [1 error]
    [1] ./client/entry.js 21 bytes {0} [built]

ERROR in multi main
Module not found: Error: Cannot resolve module 'webpack-hot-middleware/client' in /home/paralin/Documents/angular2-webpack
 @ multi main
I20160717-14:02:27.682(-7)? test
=> Started your app.

=> App running at: http://localhost:3000/
```
