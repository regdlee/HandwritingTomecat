# Mini-tomcat
简单的实现一个简易版的tomcat能够返回字符串,静态资源,处理servlet(单线程,多线程)



# 自定义版本tomcat处理请求使用说明

## 四个小版本

分别在指定包下如v1,v2,v3,v4每个代表一个版本

- v1 简单的返回指定字符串
- v2 返回静态页面
- v3 单线程处理servelt请求(多个请求会阻塞)
- v4 多线程处理
- v5 部署外部项目（多个项目，多线程处理）
  部署外部项目到webapps下面，在server.xml里面配置webapps路径以及port端口


## 说明

每个版本中`Bootstrap`类中`main`方法启动默认监听8080端口,如有需要可以提供配置到指定xml文件里;
