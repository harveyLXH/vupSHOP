# vue_shop

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
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

### 启动vue-cli 图形化(GUI)界面 命令
`vue ui`

### 启动node.js 服务 服务器端文件启动app.js文件
`node ./app.js`

### 创建子分支 
`git checkout -b login` login分支
`git branch` 切换到子分支

### 使用element UI 构建登录页面
1. 构建页面
2. 绑定input图标
3. 表单验证
4. 登录验证
5. 重置验证

### 在分支上写完功能后 合并到主分支
1.先切换到主分支 `git checkout master`
2.合并登录分支  `git merge login`
3.把本地仓库推送 `git push`
4.先切换到登录分支 然后推送并创建登录分支 `git checkout login` `git push -u origin login`

### 项目优化策略
1.生成打包报告
2.第三方库启用CDN
3.Element-UI组件按需加载
4.路由懒加载
5.首页内容定制

### 相关错误问题解决方法
https://blog.csdn.net/qq_44722915/article/details/106321079

### WARN
```
Couldn't parse bundle asset "D:\xxx\xxx\dist\app.981ed06ecb37470b9e11.hot-update.js".
Analyzer will use module sizes from stats file.
```
- 后来发现应该是Webpack Bundle Analyzer这个插件（分析项目各个数据包的大小，优化项目大小的时候有用），发出的warn，一般不大的项目不太需要这个插件，用vue-cli3.x搭建项目时就默认安装

### 去除console.log()
- 安装 babel-plugin-transform-remove-console

### vue.js项目打包时出错找不到main.js
https://blog.csdn.net/zhangyysp/article/details/111661302

### 一次webpack 的externals配置带来的优化体验
https://blog.csdn.net/w1418899532/article/details/99862713