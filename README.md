## 前言

欢迎来到我们的项目——高校校园交友微信小程序！本项目旨在为高校学生提供一个方便快捷的线上交友平台，让他们可以在这里拓展社交圈，结识志同道合的朋友。以下是关于本项目的详细介绍。

## 内容介绍

本项目采用微信小程序作为前端展示，后端采用Spring Boot技术构建。用户可以通过微信小程序实现注册、登录、查看好友动态、发布动态、添加好友等功能。同时，我们还为用户提供了丰富的个性化设置，以满足不同用户的交友需求。

## 技术介绍

本项目采用以下技术栈：

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为一段关于用户登录的核心代码：

```java
@RestController
public class UserController {

    @Autowired
    private UserService userService;

    @PostMapping("/login")
    public Result login(@RequestBody User user) {
        User result = userService.login(user);
        if (result != null) {
            return new Result(true, "登录成功", result);
        } else {
            return new Result(false, "用户名或密码错误");
        }
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/329114/2/12874/86323/68c5a0fbF124ac84b/975a391cfaa76695.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332069/8/12832/5767/68c5a0d2Fdc4f0bad/b0ea707834155341.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/331725/39/13030/18454/68c5a0d2Fc82da943/5855135285e1d19f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/331641/13/12912/32340/68c5a0d3F0afa4c7d/9106ba4c74d81221.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325120/38/19646/11600/68c5a0d3F61948d55/94f5912e2b4d05c6.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336636/1/9497/23511/68c5a0d3F75a8b2e7/498af12c8ebd9077.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339969/1/10371/35739/68c5a0d3F5c5740a1/2b1665546da7f871.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340218/11/10421/32782/68c5a0d3F34c4c4f0/e7b2266a3fd0dd71.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328752/32/19794/8123/68c5a0d3F0a777118/3b50464c2f58fa16.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344982/13/3013/9415/68c5a0d4F400ff674/309a26d4351257c8.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
