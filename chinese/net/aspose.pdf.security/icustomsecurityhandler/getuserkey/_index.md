---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF for .NET API 参考"
description: "ICustomSecurityHandler 方法。根据用户密码创建编码数组。此值通常用于检查密码是属于用户还是所有者以及获取加密密钥。加密期间调用此方法以准备并填充加密字典。调用文档加密时，用户指定的密码作为参数传入。"
type: docs
weight: 110
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

基于用户密码创建一个编码数组。此值通常用于检查密码是属于用户还是所有者，并获取加密密钥。加密过程中调用此方法以准备并填充加密字典。调用文档加密时，用户指定的密码作为参数传递。

```csharp
public byte[] GetUserKey(string userPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |

### 返回值

用户密钥数组。

### 另请参见

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


