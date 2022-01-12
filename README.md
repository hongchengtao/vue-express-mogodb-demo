# vue2.6 + express5.0 + mogodb 前后端 demo

## node-end Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run devStart （热更新）
```

## front-end Project setup

```
cd client/vueapp
```

```
npm install
```

### Compiles and hot-reloads for development

```
npm run dev
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## mongodb Windows 下的安装

下载 MongoDB 安装包，选择 Windows x64 版本安装，下载地址：https://www.mongodb.com/try/download/community

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef307d1fa5827~tplv-t2oaga2asx-watermark.image)

运行 MongoDB 安装包并选择自定义安装，设置好安装路径；

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef30802408750~tplv-t2oaga2asx-watermark.image)

配置 MongoDB，让 MongoDB 作为服务运行，并配置好数据目录和日志目录；

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef307d62e042d~tplv-t2oaga2asx-watermark.image)

取消 MongoDB Compass 的安装选项（不取消安装极慢），需要可自行安装；

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef307d999a72d~tplv-t2oaga2asx-watermark.image)

双击 mongo.exe 可以运行 MongoDB 自带客户端，操作 MongoDB；

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef307d6401f86~tplv-t2oaga2asx-watermark.image)

连接成功后会显示如下信息；

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef307d84fcf3d~tplv-t2oaga2asx-watermark.image)

## 客户端工具

首先下载客户端工具，下载地址：robomongo.org/download
![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef30800c1c130~tplv-t2oaga2asx-watermark.image)

下载完成后解压，双击 robo3t.exe 即可使用；

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef308262e0685~tplv-t2oaga2asx-watermark.image)

之后创建一个到 MongoDB 的连接；
![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef30802408750~tplv-t2oaga2asx-watermark.image)
创建连接成功以后，就可以操作 MongoDB 了。

![](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2020/5/7/171ef3082aebf282~tplv-t2oaga2asx-watermark.image)

```
参考链接
https://juejin.cn/post/6844904150635921422

```
