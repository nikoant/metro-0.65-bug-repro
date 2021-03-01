To reproduce bug with Metro 0.65.1:
```
yarn install && yarn build && yarn start
```

Changing version of "metro" to "0.64.0" in package.json and retrying the same command works as expected.
