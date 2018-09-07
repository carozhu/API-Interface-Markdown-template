# API接口Markdown文档模板

## 用户登录
---
#### 接口说明
<style>
table th:first-of-type {
    width: 100px;
}
</style>
| URL | request | version | status |
| :--- | :--- | :--- | :--- |
| [http://server_ip/v1/account/login](http://testapi.heremyhome.com/account/login) | POST | 1.0 | true |

#### 请求参数说明

| 请求参数 | 类型 | 必填 | 参数说明 | 示例 |
| :--- | :--- | :--- | :--- | :--- |
| username | String | true | 登录用户名 |carozhu |
| password | String | true | 登录密码   |123456   |

#### 返回参数说明

| 返回参数 | 参数类型 | 参数说明 |
| :--- | :--- | :--- |
| responseCode | Integer | 200：成功|
| accessToken | String | 用户token|
| ... | ... | ... |

#### 返回示例JSON

```json
{
    "responseCode": 200,
    "data": {
        "name": "carozhu",
        "type": 4,
        "version": "1.2.4",
        "file": "http://versions.update.com/xxx.apk",
        "md5": "6ed86ad3f14db4db716c808cfc1ca392",
        "description": "update for simple to you！"
    }
}
```

#### code码说明

| code | msg | desc |
| :--- | :--- | :--- |
| 200 | success |  |

#### 接口详细说明 

``` 
如有特别说明请描述

```

---

#### 备注
``` 
关于其它错误返回值与错误代码，参见 [Code码说明](#Link)

```
---
#### Author

| Coder   | 创建时间 | 更新时间 |联系方式 |
| :---     | :---| :--- | :--- |
| carozhu  | 2018.4.28 |2018.5.29  |1025807062@qq.com  |


