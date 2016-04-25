Run the following to see the failure...

```shell
npm install
babel-node .
# or
mocha --colors --reporter spec --compilers js:babel-register test.js
```
