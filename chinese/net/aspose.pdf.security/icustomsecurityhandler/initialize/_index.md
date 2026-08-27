---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF for .NET API 参考"
description: "ICustomSecurityHandler 方法。用于初始化当前实例以进行加密。请注意，在加密时，它将填充已传输的属性 ICustomSecurityHandler 的数据，并在从加密字典打开文档时使用这些数据。如果在新加密期间调用此方法，则 UserKey 和 OwnerKey 将为 null。"
type: docs
weight: 120
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

用于初始化当前实例以进行加密。请注意，在加密时，它将填充已传输的属性 [`ICustomSecurityHandler`](../) 的数据，并在从加密字典打开文档时使用这些数据。如果在新加密期间调用此方法，则 [`UserKey`](../../encryptionparameters/userkey/) 和 [`OwnerKey`](../../encryptionparameters/ownerkey/) 将为 null。

```csharp
public void Initialize(EncryptionParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 参数 | EncryptionParameters | 加密参数。 |

### 另请参见

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


