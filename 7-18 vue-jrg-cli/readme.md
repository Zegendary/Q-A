# vue-jrg-cli

```js
-dist //输出目录
-assert //静态资源目录
-src //核心代码目录
-src/components //组件目录
-index.html //入口html
-package.json //项目依赖管理文件
-webpack.config.js //webpack 配置
```

### 如何运行

1. `git clone git@github.com:Zegendary/Q-A.git` 克隆仓库到本地
2. `cd 7-18 vue-jrg-cli`
3. `npm install` 安装所需依赖
4. `npm start` 启动项目
5. 打开 `http://localhost:8080/` 

如果需要push到github 在线预览的话 请输入命令 `webpack` 将文件打包并配合githubpage即可。

注： 大部分代码都有注释 配合[vue官方文档](https://cn.vuejs.org/v2/guide/installation.html),可以自己写写东西了。实际开发仍推荐使用 `vue-cli`


### 今日问答

#### 响应式

1. 针对pc端 浏览器视口不同大小的响应式
2. 针对移动端手机屏幕不同大小的响应式
3. 页面同时兼容pc+mobile 的响应式

[举例网站](https://cn.vuejs.org/v2/guide/installation.html)