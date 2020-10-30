# JimuReport

积木报表，像搭建积木一样在线设计报表
v1.0-beta

```
永久免费使用
专注于设计“专业 易用 优质”的大屏设计器和报表设计器
```

离线版与JeecgBoot集成
-----------------------------------

- 第一步： 集成依赖 jar
```
<dependency>
  <groupId>org.jeecgframework.boot</groupId>
  <artifactId>jimureport</artifactId>
  <version>1.0-beta</version>
</dependency>
``` 

- 第二步： 执行升级 sql

    [jimureport_init20201029.sql](https://github.com/zhangdaiscott/JimuReport/blob/master/db/jimureport_init20201029.sql "jimureport_init20201029.sql")

- 第三步：修改配置文件
   修改 application-dev.yml增加配置

```
#jeecg专用配置
jeecg :
  #积木报表设置
  jmreport:
    mode: dev
    #是否需要校验token
    is_verify_token: false
    #必须校验方法
    verify_methods: remove,delete,save,add,update
```


- 第四步： 角色授权菜单，就可以看到报表设计菜单

![](https://oscimg.oschina.net/oscnet/up-e35b2318b8db9673fa064a0b50087bdd234.png)


- 第五步： 进入报表设计器列表

![](https://oscimg.oschina.net/oscnet/up-03d6c0a82f8e2fb96783eb5d9ce9a6a7bc0.png)

**=>开放的功能清单**

![](https://oscimg.oschina.net/oscnet/up-d10e6c78dd5fb37923d3123be8c1ca23cd0.png)





项目介绍
-----------------------------------

- 官网： www.jimureport.com
- 视频： https://www.bilibili.com/video/BV1iT4y1w78o
- 免费使用： http://jimureport.com/login

