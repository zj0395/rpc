# RPC调用框架
[![Build Status](https://travis-ci.com/zj0395/rpc.svg?branch=master)](https://travis-ci.com/zj0395/rpc)  
## 代码结构
- src:  
    - Common: 公用代码  
    - Client: 客户端代码  
    - Server: 服务端代码  
- test: 测试代码  
- extern:  
    - fmt  c++字符串格式化
    - protobuf 将协议二进制序列化
    - spdlog  日志
    - gtest  测试
## Install
git clone https://github.com/zj0395/Chat.git  
git submodule init  
git submodule update  
## Build
- 初次构建`./build.sh -A`
- `./build.sh -h` 查看构建帮助
