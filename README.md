>整合使用 koa 框架常用的中间件工程,目的是使用该工程可以快速开始项目开发
**建议每隔一个月检查下依赖插件是否有新版本，保持所有依赖包都是最新版本**


## 开发环境(`process.env.NODE_ENV === 'development'`)
- 不对请求 api 进行权限验证
- 创建的数据库 `kuku`,数据库用户名和密码 `kuku:kuku`
- 会自动初始化 11 用户数据


## 工程中包含的组件
- [koa-basic-auth](https://www.npmjs.com/package/koa-basic-auth) 网站访问基础认证(弹出的一个输入用户名和密码的框)


## 资源
- [LinkedIn 授权应用创建](https://www.linkedin.com/developer/apps)