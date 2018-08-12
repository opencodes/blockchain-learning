# blockchain-development

## Install on windows
### Set 
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

```
git config --system http.sslverify false
```

```
npm install -g node-gyp
```
```
npm install --global --production windows-build-tools
```
```
npm install -g ethereumjs-testrpc```
```
```
npm install -g truffle
```

## Development

- Create Contract
```
truffle compile
```

``` 
truffle migrate
```

``` 
truffle console
> var hw
> HelloWorld.deployed().then(function(deployed){hw=deployed;})
> hw.sayHello()
> 'Hello 2018!'
```
