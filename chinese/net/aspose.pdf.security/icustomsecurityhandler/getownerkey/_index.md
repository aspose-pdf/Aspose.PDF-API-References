---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF for .NET API 参考"
description: "ICustomSecurityHandler 方法。根据密码创建一个编码数组，该数组将写入加密字典的 O 字段。应仅依赖传入的参数。可以使用 owner password 从此字段计算用户密码。此方法在加密期间调用，以准备并填充加密字典。该值将在 CalculateEncryptionKey 中可用，以从 UserKey 获取密钥。调用文档加密时用户指定的密码将被传递。密码可能未指定，或只指定一个。"
type: docs
weight: 100
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

根据密码创建一个编码数组，该数组将写入加密字典的 O 字段。应仅依赖传入的参数。可以使用 owner password 从此字段计算用户密码。此方法在加密期间调用，以准备并填充加密字典。该值将在 [`CalculateEncryptionKey`](../calculateencryptionkey/) 中可用，以从 UserKey 获取密钥。调用文档加密时用户指定的密码将被传递。密码可能未指定，或只指定一个。

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |

### 返回值

所有者密钥的数组。

### 另请参见

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


