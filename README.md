crisn-ui ![alt tag](https://img.shields.io/badge/vue-2.6.10-brightgreen.svg)
==============================

`crisn-ui`是一个后台前端解决方案，它基于 vue 和 element-ui实现。

## Environment
+ `Vue:` 2.6.12
+ `Element-UI:` 2.15.6
+ `Echarts:` 4.9.0

## Project
```
├── build                      # 构建相关
├── mock                       # 项目mock 模拟数据
├── public                     # 静态资源
│   │── favicon.ico            # favicon图标
│   └── index.html             # html模板
├── src                        # 源代码
│   ├── api                    # 所有请求
│   ├── assets                 # 主题 字体等静态资源
│   ├── components             # 全局公用组件
│   ├── directive              # 全局指令
│   ├── filters                # 全局 filter
│   ├── layout                 # 全局 layout
│   ├── router                 # 路由
│   ├── store                  # 全局 store管理
│   ├── utils                  # 全局公用方法
│   ├── views                  # views 所有页面
│   ├── App.vue                # 入口页面
│   ├── main.js                # 入口文件 加载组件 初始化等
│   └── permission.js          # 权限管理
├── .env.xxx                   # 环境变量配置
├── .eslintrc.js               # eslint 配置项
├── .babei.config.js           # babel 配置
├── vue.config.js              # vue-cli 配置
├── postcss.config.js          # postcss 配置
└── package.json               # package.json
```

## Run
```bash
# 进入项目目录
cd crisn-ui

# 安装依赖
npm install

# 解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

## Release
```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```