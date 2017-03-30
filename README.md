## 说明
本模板 fork 自[S7venYoung/SpechtLiteConf-ADB](https://github.com/S7venYoung/SpechtLiteConf-ADB)，在他的配置文件基础上增加了一份负载均衡的配置文件。
- 本人不是程序员，如有违反某些规定，请告知。
# 配置模板 for [SpechtLite](https://github.com/zhuhaow/SpechtLite)

## 配置文件说明
- **Conf.yaml**: SpechtLite 主要代理配置文件

- **load-balance.yaml**：自动选择线路，并自动区分日本 IP 的

- **Proxylist**: 强制代理列表，可以把自己想要强制代理的域名加入进去，如：
```
baidu\.com
```
- **directiprange**: 直连列表，来自 [china_ip_list](https://github.com/17mon/china_ip_list)

- **rejectlist**: 部分来自 [BurpSuite](https://raw.githubusercontent.com/BurpSuite/CloudGate-RuleList/master/Rule/REJECT)，部分来自 abclite 的 Surge 文件，全面去 YouTube、优酷、乐视、腾讯等视频广告。

- **proxyiprange**: 加入 telegram and Amazon EC2 IPs

## 注意：

包中包含两份 yaml 文件，一份为单线路代理文件，load-balance.yaml 为负载均衡文件。

## 使用方法
> 1. 配置 load-balance.yaml 代理信息；
> 2. 复制文件到 `~/SpechtLiteConf`

## 具体图文教程
> 1. [微信链接](http://mp.weixin.qq.com/s/nIIZ7KprczpcBUUSsWDh2Q)

## MIT License (MIT)

The MIT License (MIT)

Copyright (c) 2016-2017 geekpi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

