# [Did] Decentralized Identity Dapp 
it is a decentralized application for people using decentralized identity. 

## Introduction
这是一个去中心化的身份标识管理应用，类似与[Metamask](https://docs.metamask.io/)
用户在Dapp中通过web3地址创建属于自己的did，每个did身份标识是独一无二的
```example
did:eth:0x1234567890
```
一个地址可以创建多个did，每个did可以绑定多个证书，每个证书都对应一个公钥，根据did uri 可以获取到对应的公钥
```example
did:eth:0x1234567890#key-student
```
根据did uri 可以获取到对应的证书公钥，可以用来验证证书有效性


## Features
- [x] 创建did
- [x] 创建证书
- [x] 创建did document
- [x] did 隐私控制
- [x] did绑定证书
- [x] 证书签名
- [x] 证书验证
- [x] 证书撤销
- [x] 证书查询

## 开发计划

希望有兴趣的人可以一起协助开发，欢迎提出issue和pr



