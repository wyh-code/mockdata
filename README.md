
## [官网地址](https://www.mockdata.cn/)

## 个人使用 
***

### 1、扫描二维码登录，进入项目列表
![login](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/aa4cfa32fd2f41e5aedca222c39b3bf7~tplv-k3u1fbpfcp-zoom-1.image)

### 2、新增项目
![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/bb71945f33f7405fb73a72dbb33c575e~tplv-k3u1fbpfcp-zoom-1.image)

### 3、点击项目名称，进入项目
![pro](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/1a79c184e60a4c728e80402afb1e8d36~tplv-k3u1fbpfcp-zoom-1.image)

### 4、新增 api
![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/1eedc117df1745858a60b6ae1a304d87~tplv-k3u1fbpfcp-zoom-1.image)

### 5、编辑 api（设置 method，请求参数，响应数据）
![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/f91bb08ac3254f95adce0f0e7ff151d6~tplv-k3u1fbpfcp-zoom-1.image)

### 6、复制请求地址，发送请求
![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/51177a6542094bfe8483fefffc82dc9f~tplv-k3u1fbpfcp-zoom-1.image)


```js
 // 可以直接调用
 axios.get('http://api.mockdata.cn/WK9Dr7EutbJi/mock/api')
 
 // 或在 webpack 配置
 proxy: {
  "/api": {
    target: 'http://api.mockdata.cn/WK9Dr7EutbJi/',
    pathRewrite: {"^/api" : ""}
  }
}
```


***
## 请求校验

**mockdata 对入参及 method 做了校验**

![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/df3ac368790f4ab881a0430f3cd722ac~tplv-k3u1fbpfcp-zoom-1.image)

**返回正确数据**

![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/1dafdf60067d4ce799aa1329af762c69~tplv-k3u1fbpfcp-zoom-1.image)

<br/> 

## 团队协作
***
在项目中，可以通过添加成员，来进行团队协作。在项目初期，后端接口尚未完成时，后端同学可通过该功能，定义接口信息，为前端同学提供 mock 数据。

### 获取用户id
![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4c360bd5d9be4bd4aedaf3a3bd94ed81~tplv-k3u1fbpfcp-zoom-1.image)
### 添加成员
![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e208f74be25d454a81a5505bfad00be5~tplv-k3u1fbpfcp-zoom-1.image)

<br/>

## 公众号
***
### 关注公众号

![关注公众号](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e84189c1eb7e45f480a1b94203904d51~tplv-k3u1fbpfcp-zoom-1.image)

### 获取签到口令

![project](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/8740e053af89400c894c3f4d8529c779~tplv-k3u1fbpfcp-zoom-1.image)

### 完成签到
![签到](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/200de4a03f9b4f5882a2b4552ffb718d~tplv-k3u1fbpfcp-zoom-1.image)

### 注：每次签到有效期为24小时。

***

**签为只为维护服务器运维成本，望谅解。**

***

### 最后
***
由于作者精力有限，该网站或有遗漏 BUG 未曾发现修复，欢迎大家提出反馈，作者将尽快修复提出的问题。   
再次感谢！！！