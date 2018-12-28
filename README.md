# fast-cache

短小精悍的前端缓存工具，防止内存“侧漏”。

## 简介

特色 （推广的一些亮点）

## 安装下载

- 下载地址 https://github.com/LiuByron/fast-cache/releases
- `npm i fast-cache-555`
- CDN http://unpkg.com/fast-cache-555/release/bundle.js

git clone git@github.com:LiuByron/fast-cache.git

npm install

npm dev 启动

npm build 打包

## 快速使用

```js
var FC = window.FastCache;
var cache = new FC();
cache.set('a', 100);
alert(cache.get('a'));
console.log(cache.clear())
```

- [使用文档](./doc/use/README.md)
- [二次开发文档](./doc/dev/README.md)

## 交流 & 提问

- 提问：https://github.com/LiuByron/fast-cache/issues
- QQ群、微信群（及时反馈，及时回复社区）

## 关于作者

- 个人主页
- 收款二维码
