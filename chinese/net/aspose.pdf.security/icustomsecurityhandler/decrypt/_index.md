---
title: "ICustomSecurityHandler.Decrypt"
second_title: "Aspose.PDF for .NET API 参考"
description: "ICustomSecurityHandler 方法。解密数据数组"
type: docs
weight: 70
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler.Decrypt method

解密数据数组。

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | Byte[] | 要解密的数据。 |
| objectNumber | Int32 | 包含加密数据的对象编号。 |
| generation | Int32 | 对象的代数。 |
| 键 | Byte[] | 通过 CalculateEncryptionKey 方法获取的密钥 |

### 返回值

解密后的数据。

### 另请参见

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


