# gin-mvc

框架目录
--------------------------
```tree
 ezijing@bogon  ~/go/src/gin-mvc  tree
.
├── README.md
├── config
│   └── app.ini 项目配置文件
├── constants 常量
│   └── system.go 系统常量
├── controllers 控制器
│   ├── api 接口
│   │   └── v1
│   │       ├── tag.go
│   │       └── test.go
│   └── controller.go 接口基类
├── go.mod
├── go.sum
├── main.go 
├── middleware 中间件
├── models 模型
│   └── models.go
├── pkg 内部包
│   ├── exception 异常
│   │   ├── code.go 错误码
│   │   └── msg.go 错误码说明
│   ├── setting 配置
│   │   └── setting.go
│   └── util 工具
│       └── pagination.go
├── routers 路由配置
│   ├── router.go 路由注册入口
│   └── test.go
└── runtime 运行时文件

```