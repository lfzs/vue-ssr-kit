# Vue SSR 脚手架

## 使用

`yarn start`

## 说明

- 路由组件的 `asyncFetchData` 方法为服务端调用入口。
客户端组件通过混入 `beforeMount` 生命周期将服务端 `asyncFetchData` 结果赋值到 `this.asyncData`

## TODO

- http-proxy-middleware 代理

- koa 热部署、log 记录

- util、store
