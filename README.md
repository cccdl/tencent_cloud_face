# 腾讯云 - 人脸核身sdk ！

### 主要新特性

* 腾讯云 - 人脸核身 SDK FOR PHP
* 调用简单，统一原样返回
* 所有方法的实例详细使用examples

### 更新日志

- 1.0.0 发布

## 安装

> 运行环境要求PHP7.1+。

```shell
$ composer require cccdl/tencent_cloud_face
```

### 接口对应文件

| 文件      | 方法                  | 说明              |
|---------|---------------------|-----------------|
| App.php | `getAccessToken()`  | 获取 Access Token |
| App.php | `getNonceTicket()`  | 获取NONCE Ticket  |
| App.php | `getSignTicket()`   | 获取SIGN Ticket   |
| App.php | `getFaceId()`       | 获取faceId        |
| App.php | `getSign()`         | 签名方法            |
| App.php | `queryfacerecord()` | 服务器获取结果         |

```使用方法
查看test文件夹内的测试文件
如：testQueryfacerecord 方法
```

## 文档

[腾讯云-人脸核身](https://cloud.tencent.com/document/product/1007)

## 问题

[提交 Issue](https://github.com/cccdl/tencent-cloud-face/issues)，不符合指南的问题可能会立即关闭。

## Contributing

You can contribute in one of three ways:

1. File bug reports using the [issue tracker](https://github.com/cccdl/tencent-cloud-face/issues).
2. Answer questions or fix bugs on the [issue tracker](https://github.com/cccdl/tencent-cloud-face/issues).
3. Contribute new features or update the wiki.

_The code contribution process is not very formal. You just need to make sure that you follow the PSR-0, PSR-1, and
PSR-2 coding guidelines. Any new code contributions must be accompanied by unit tests where applicable._

## License

MIT
