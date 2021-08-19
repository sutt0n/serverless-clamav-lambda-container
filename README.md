## AWS ClamAV Lambda container & a service using it to scan files via S3 triggers
```
git clone https://github.com/sutt0n/serverless-clamav-layer
sls deploy
```

## Unit Tests
There's only one unit test for our handler, but to run it you'll need to install the `devDependencies` 

```
npm i
npm run test
```