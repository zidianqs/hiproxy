# hiproxy
A Node.js proxy client

[![Build Status](https://travis-ci.org/zdying/hiproxy.svg?branch=master)](https://travis-ci.org/zdying/hiproxy)
[![Coverage Status](https://coveralls.io/repos/github/zdying/hiproxy/badge.svg?branch=master)](https://coveralls.io/github/zdying/hiproxy?branch=master)
[![npm](https://img.shields.io/npm/v/hiproxy.svg)](https://www.npmjs.com/package/hiproxy)
[![Node.js version](https://img.shields.io/badge/node-%3E%3D0.12.7-orange.svg)](https://nodejs.org/)
[![license](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/zdying/hiproxy/blob/master/LICENSE)

# 安装

```bash
npm install -g hiproxy
```

# 使用

1. 启动服务
```bash
cd your_workspace
hiproxy start -p 5525 --debug
```

2. 设置代理

```bash
127.0.0.1:5525
```

# Help

```bash
  Usage:

    hiproxy [command] [option]

  Commands:

    start  启动代理服务

  Options:

    -v, --version   显示版本信息
    -h, --help      显示帮助信息
    -d, --debug     显示调试信息
    -D, --detail    显示详细调试信息
    --log-time      显示日志时间
```

# TODO

## 核心功能

- [x] ~~配置文件解析（Nginx风格配置文件）~~
- [x] ~~HTTP代理~~
- [x] ~~HTTPS代理~~
- [ ] HTTPS证书生成
- [x] ~~启动浏览器并设置代理~~
- [ ] 生成自动代理文件
- [ ] 完善文档
- [ ] 完善测试

## 其他

### Node.js API

- [ ] 基本API
- [ ] 配置文件查找接口
- [ ] 配置文件名称接口
- [ ] 指令扩展
- [ ] ...
