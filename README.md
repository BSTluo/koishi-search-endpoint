<!-- PROJECT LOGO -->

<br />
<div align="center">
  <a href="https://github.com/initialencounter/mykoishi">
    <a href="https://koishi.chat/" target="_blank">
    <img width="160" src="https://koishi.chat/logo.png" alt="logo">
  </a>
  </a>

<h3 align="center">koishi-search-endpoint</h3>

<p align="center">
    搭建自己的Koishi插件市场源叭！
  </p>
</div>

### 说明：

在启动后，会每隔1分钟将官方源下载到本地。

当访问本地的11451端口后，会将本地的官方源Json文件输出，从而达到分发官方源的作用

### 使用方法：

```javascript

// 1. 从github上下载包
git clone https://github.com/BSTluo/koishi-search-endpoint.git
// 上面这条失败的话，选择执行下面这条
git clone https://ghproxy.com/https://github.com/BSTluo/koishi-search-endpoint.git
// 2. 进入文件夹
cd koishi-search-endpoint

// 3. 下载依赖包
npm i

// 4. 运行它！
node index.js

// 5. 在koishi中将market插件的search.endpoint修改为
http://127.0.0.1:11451

// 6. 碎了怎么办！把market插件的search.endpoint修改为
https://registry.koishi.chat/index.json

```
