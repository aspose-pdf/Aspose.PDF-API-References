---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Aspose.PDF for .NET API 参考"
description: "ICustomSecurityHandler 方法。加密文档的权限字段。结果将写入 Perms 加密字典字段。打开文档时，可通过 EncryptionParameters 的 Perms 字段获取该值。允许您检查文档权限是否已更改"
type: docs
weight: 90
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

加密文档的权限字段。结果将写入 Perms 加密字典字段。打开文档时，可通过 [`EncryptionParameters`](../../encryptionparameters/) 的 Perms 字段获取该值。允许您检查文档权限是否已更改。

```csharp
public byte[] EncryptPermissions(int permissions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 权限 | Int32 | 文档权限的整数表示。 |

### 返回值

加密的数组。

### 另请参见

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


