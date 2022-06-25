# node-red-es6-shim

This is an ES6 shim to enable e.g.
[node-red-node-template](https://github.com/yostinso/node-red-node-template)
by making it possible to type check an ES6 class that inherits from Node RED
nodes since they are created via `util.inherits` and are not actually
subclasses.
