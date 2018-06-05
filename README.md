## Welcome to struts2

模型-视图-控制，使业务逻辑与视图显示分离。

### 搭建struts2环境

导包→struts2.xml→web.xml→测试(struts2工作流程);

### struts2 前台→后台

页面访问方法;参数传递后台;

### struts2 后台→前台

 获取前台参数;处理前台参数;跳转前台页面;
 
### struts2 前台→展示
 
 获取后台数据;流程控制标签;
 
### struts2 对异常的处理

 方法(一) web.xml中配置<error-page></error-page>;
 方法(二) struts.xml中配置 全局异常映射 全局结果集;

### struts2 对配置文件的处理

 多人团队开发中，不可避免同时操作struts2.xml,
 ```java
 <include file="user.xml"></include> ``` //java
 
