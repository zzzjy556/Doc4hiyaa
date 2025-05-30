---
outline: deep
---

## WebVirtMgr 安装指南

[![hits](https://hits.spiritlhl.net/webvirtcloud.svg?action=hit&title=hits&title_bg=%23555555&count_bg=%233aebee&edge_flat=false)](https://hits.spiritlhl.net)

仓库地址: <https://github.com/oneclickvirt/webvirtcloud>

原项目对应仓库：<https://github.com/retspen/webvirtmgr>

## 控制节点和计算节点同时安装

- 支持系统：Debian[8,9,10]，Ubuntu[16.04,18.04,20.04]
- 系统会自动编译python的2.7的安装包后再进行部署，编译过程中会有报错提示但不用理会，只要脚本还在跑就说明一切正常

国际

```bash
curl -slk https://raw.githubusercontent.com/oneclickvirt/webvirtcloud/main/scripts/install_webvirtmgr.sh -o install_webvirtmgr.sh \
&& chmod +x install_webvirtmgr.sh \
&& bash install_webvirtmgr.sh
```

国内

```bash
curl -slk https://cdn.spiritlhl.net/https://raw.githubusercontent.com/oneclickvirt/webvirtcloud/main/scripts/install_webvirtmgr.sh -o install_webvirtmgr.sh \
&& chmod +x install_webvirtmgr.sh \
&& bash install_webvirtmgr.sh
```

## 缺点

原项目已经不再有维护，完全不推荐使用。
