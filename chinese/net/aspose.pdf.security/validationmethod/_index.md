---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod 枚举。表示用于证书验证的方法的枚举
type: docs
weight: 10050
url: /zh/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod 枚举

表示用于证书验证的方法的枚举。

```csharp
public enum ValidationMethod
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 自动确定证书验证的最佳方法。 |
| Ocsp | `1` | 使用在线证书状态协议 (OCSP) 进行证书验证。OCSP 是一种通过直接查询颁发证书的证书授权机构 (CA) 来提供证书验证状态的协议。 |
| Crl | `2` | 使用证书撤销列表 (CRL) 方法验证证书。 |
| All | `3` | 使用所有可用方法 (OCSP 和 CRL) 进行证书验证。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* 程序集 [Aspose.PDF](../../)