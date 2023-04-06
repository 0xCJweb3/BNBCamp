# 用hardhat部署可升级合约

部署管理合约(ProxyAdmin)
```
npx hardhat deploy --tags ProxyAdmin --network bnbtest
```


部署代理合约和逻辑合约
```
npx hardhat deploy --tags MyContract --network bnbtest
```

