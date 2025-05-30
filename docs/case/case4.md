---
outline: deep
---

# 仓库

https://github.com/oneclickvirt/backtrace

[![Hits](https://hits.spiritlhl.net/backtrace.svg?action=hit&title=Hits&title_bg=%23555555&count_bg=%230eecf8&edge_flat=false)](https://hits.spiritlhl.net)

# backtrace

三网回程路由线路测试

基于 https://github.com/zhanghanyun/backtrace 的重构和优化，与原版存在很大不同

路由的线路判断最终还是得人工判断的才准确，本项目测试结果仅供参考

## 功能

- [x] 检测回程显示IPV4地址时的线路，不显示IP地址时显示ASN检测不到，原版[backtrace](https://github.com/zhanghanyun/backtrace)也支持
- [x] 支持对```4837```、```9929```和```163```线路的判断，原版[backtrace](https://github.com/zhanghanyun/backtrace)也支持
- [x] 支持对```CN2GT```和```CN2GIA```线路的判断，原版[backtrace](https://github.com/zhanghanyun/backtrace)不支持
- [x] 支持对```CMIN2```和```CMI```线路的判断，原版[backtrace](https://github.com/zhanghanyun/backtrace)不支持
- [x] 支持对整个回程路由进行线路分析，与原版[backtrace](https://github.com/zhanghanyun/backtrace)仅进行一次判断不同
- [x] 修复原版[backtrace](https://github.com/zhanghanyun/backtrace)对IPV4地址信息获取时json解析失败依然打印信息的问题
- [x] 增加对全平台的编译支持，原版[backtrace](https://github.com/zhanghanyun/backtrace)仅支持linux平台的amd64和arm64架构

## 使用

```shell
curl https://raw.githubusercontent.com/oneclickvirt/backtrace/main/backtrace_install.sh -sSf | sh
```

更多架构请查看 https://github.com/oneclickvirt/backtrace/releases/tag/output

## 概览图

![图片](https://github.com/oneclickvirt/backtrace/assets/103393591/4688f99f-0f02-486f-8ffc-78d30f2c2f95)

![图片](https://github.com/oneclickvirt/backtrace/assets/103393591/2812a47d-4e6b-4091-9bb9-596af6c3c8bc)

![图片](https://github.com/oneclickvirt/backtrace/assets/103393591/2e5cc625-e0da-41ff-85ff-9d21c01114a3)
