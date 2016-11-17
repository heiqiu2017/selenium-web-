# DDT

DDT Data Drive Test，数据驱动测试，也称为参数化。

## DDT 方案一：js 数据文件

## DDT 方案二：CVS 数据文件 

## DDT 方案三：XML 数据文件

通过下面三个 js 扩展，实现对 XML 数据文件载入和读取操作。

- [user-extensions.js](user-extensions.js)
- [goto_sel_ide.js](goto_sel_ide.js)
- [datadriven.js](datadriven.js) 

### 安装配置

如下图所示：

![options](images/options.png)

### 文件格式

XML 数据文件格式如下所示：

```xml
<testdata>
  <test varname="value" />
  <test varname="value" />
  <test varname="value" />
</testdata>
```

### 被测网站：百度

百度：http://www.baidu.com

_测试案例及数据文件_

- [baiduSearch.html](baiduSearch.html)  
  打开百度首页，搜索若干关键字
- [baiduSchData.xml](baiduSchData.xml)  
  本 XML 格式的数据文件包含了需要在百度上检索的关键字列表

### 被测网站：51CTO 学院

51CTO学院：http://edu.51cto.com

_测试案例及数据文件_

- [studyLens.html](studyLens.html)  
  统计学生学习总时长和平均时长
- [studentData.xml](studentData.xml)   
  本 XML 格式的数据文件包含了学生学习记录的 URL 地址列表 

### 被测网站：hosted redmine

hosted redmine：http://www.hostedredmine.com/

_测试案例及数据文件_

- [loginHRedmine.html](loginHRedmine.html)  
  不同账户的登录身份验证，两个变量：用户名和密码。

### 被测网站：ATOOL

ATOOL 手机号码归属地查询：【待补充】

_测试案例及数据文件_

- 作业

## DDT 方案：JSON 数据文件

【貌似还没有资料】