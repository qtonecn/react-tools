# react-tools

### 最下方增加版本更新日志😁

### 前言
  启动和打包的时间都稍长，请耐心等待

- [GitHub地址](https://github.com/sujunming/react-tools)

### 依赖模块
<span style="color: rgb(184,49,47);">项目是用create-react-app创建的，主要还是列出新加的功能依赖包</span>

<span style="color: rgb(184,49,47);">点击名称可跳转相关网站😄😄</span>

- [react](https://facebook.github.io/react/)(<span style="color: rgb(243,121,52);">react</span>)
- [react-router](https://react-guide.github.io/react-router-cn/)(<span style="color: rgb(243,121,52);">react路由</span>)
- [antd](https://ant.design/index-cn)(<span style="color: rgb(243,121,52);">蚂蚁金服开源的react ui组件框架</span>)
- [axios](https://github.com/mzabriskie/axios)(<span style="color: rgb(243,121,52);">http请求模块，可用于前端任何场景，很强大👍</span>)
- 其他小细节省略

### 功能模块
<span style="color: rgb(184,49,47);">备注：项目只引入了ant-design的部分组件，其他的组件antd官网有源码，可以直接复制到项目中使用，后续有时间补上全部组件。</span>
<span style="color: rgb(184,49,47);">项目使用了antd的自定义主题功能-->黑色，若想替换其他颜色，具体操作请查看antd官网</span>
<!--more-->
### 代码目录
```js
+-- build/                                  ---打包的文件目录
+-- config/                                 ---npm run eject 后的配置文件目录
+-- src/                                    ---核心代码目录
|   +-- axios                               ---http请求demo
|   |    --- index.js
|   +-- components                          ---各式各样的组件存放目录
|   +-- javascript                          ---接口api 
|   +-- styles                               ---项目的样式存放目录
|   --- App.js                              ---组件入口文件
|   --- index.js                            ---项目的整体js入口文件，包括路由配置等
--- .env                                    ---启动项目自定义端口配置文件
--- package.json                                    
```
### 安装运行
##### 1.下载或克隆项目源码
##### 2.npm安装相关包文件(国内建议增加淘宝镜像源，不然很慢，你懂的😁)
```js
npm i
```
##### 3.启动项目
```js
npm start
```
##### 4.打包项目
```js
npm run build
```

### 结尾
该项目会不定时更新，后续时间会添加更多的模块

若有问题，可加QQ群221859379与我交流

如果对你有帮助，给个star哟~~❤️❤️❤️❤️

文档转载于react-admin