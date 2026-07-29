---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF for .NET API 参考"
description: "ICustomSecurityHandler 方法。计算 EncryptionKey。通常密钥是基于 UserKey 计算的。您可以使用 EncryptionParams 中的值，该对象包含调用时的当前参数。此值作为 key 参数传递给 Encrypt 和 Decrypt。"
type: docs
weight: 60
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

计算 EncryptionKey。通常密钥是基于 UserKey 计算的。您可以使用 EncryptionParams 中的值，该对象包含调用时的当前参数。此值作为 key 参数传递给 [`Encrypt`](../encrypt/) 和 [`Decrypt`](../decrypt/)。

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用户输入的密码。 |

### 返回值

加密密钥的数组。

### 另请参见

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


