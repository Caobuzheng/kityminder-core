KityMinder Core
==========

## 简介

KityMinder（百度脑图），现在希望其变为DAG的编辑器。

对本组件进行魔改：

* KityMinder是针对的Tree的，而我需要的是个Dag，有向无环图。
* 脑图中的root, 直接使用dag的文件名，需要read only
* 汇聚的node。如何画图


## 开发说明

1. 安装 [bower](http://bower.io/#install-bower)
2. 安装 [npm](https://www.npmjs.com/get-npm)

```bash
bower install
npm install
npm install -g grunt-cli 
npm run dev # 将dev页面进行前端展示
```
