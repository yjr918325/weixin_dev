
# unionpay wechat java tool
=======

# 银联微信服务java工具

----

## 步骤：

### 项目地址
内网：
  http://172.24.19.33:3000/unionpay_wechat_tool.git

外网：
  项目组vpn账号：up_jm100057@unionpay.com
  密码：Upwc@9999
  连接vpn后再访问内网地址

### 订阅号和服务号，在maven项目中添加：

```xml
<dependency>
  <groupId>me.chanjar</groupId>
  <artifactId>weixin-java-mp</artifactId>
  <version>1.3.3</version>
</dependency>
```

# 企业号应用，在你的maven项目中添加：

```xml
<dependency>
  <groupId>me.chanjar</groupId>
  <artifactId>weixin-java-cp</artifactId>
  <version>1.3.3</version>
</dependency>
```


### 获取项目文件config.xml中的app信息
  <appId>公众号appID</appId>
  <secret>公众号appsecret</secret>
  <token>公众号Token</token>
  <aesKey>公众号EncodingAESKey</aesKey>
  <accessToken>可以不填写</accessToken>
  <expiresTime>可以不填写</expiresTime>
