
## [官网地址](https://www.mockdata.cn/)

### 个人使用 
***

#### 1、扫描二维码登录，进入项目列表
![login](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/login.png)

#### 2、新增项目
![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/project.png)

#### 3、点击项目名称，进入项目
![pro](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/pro.png)

#### 4、新增 api
![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/addApi.png)

#### 5、编辑 api（设置 method，请求参数，响应数据）
![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/editApi.png)

#### 6、复制请求地址，发送请求
![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/url.png)


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
### 请求校验

**当提示以下信息时，请先前往公众号签到**

![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/req.png)

**mockdata 对入参及 method 做了校验**

![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/check.png)

**返回正确数据**

![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/res.png)

<br/> 

### 团队协作
***
在项目中，可以通过添加成员，来进行团队协作。在项目初期，后端接口尚未完成时，后端同学可通过该功能，定义接口信息，为前端同学提供 mock 数据。

#### 获取用户id
![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/id.png)
#### 添加成员
![project](https://raw.githubusercontent.com/wyh-code/mockdata/master/img/addPerson.png)


<br/> 

### 最后
***
由于作者精力有限，该网站或有遗漏 BUG 未曾发现修复，欢迎大家提出反馈，作者将尽快修复提出的问题。   
再次感谢！！！