# Token Generator

使用SDK访问好视通云通信平台服务需要使用Token，该项目提供生成Token的Java语言代码。
关于Token鉴权的具体细节，参考[开发者中心](http://paas.hst.com/developer)

## 使用方式
你应该在服务器程序中使用对应的代码生成Token，将Token下发给客户端登录好视通云通信平台。

使用示列代码：

```Java
FspToken tokenBuilder = new FspToken();
tokenBuilder.setAppId(APP_ID);
tokenBuilder.setSecretKey(APP_SECRETKEY);
tokenBuilder.setGroupId(groupId);
tokenBuilder.setUserId(userId);

String tokenBuilder = tokenBuilder.build()
```

## 欢迎提交你的token生成代码
如果您对现有代码有任何改进建议，欢迎提交pull request，我们将非常感谢。

## 联系我们

- 完整的 API 文档见 [开发者中心](http://paas.hst.com/developer)