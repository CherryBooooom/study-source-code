## Vue.js 技术揭秘
https://ustbhuangyi.github.io/vue-analysis/

## 目录
src
├── compiler        # 编译相关 
├── core            # 核心代码 
├── platforms       # 不同平台的支持
├── server          # 服务端渲染
├── sfc             # .vue 文件解析
├── shared          # 共享代码

## Flow
由于使用了Flow, vscode报错，设置"javascript.validate.enable": false

## Yarn

## 源码构建
Rollup
入口：`/scripts/build.js`

## vue 入口
在 web 应用下， `Runtime + Compiler` 构建出来的 `Vue.js`，它的入口是 `src/platforms/web/entry-runtime-with-compiler.js`

