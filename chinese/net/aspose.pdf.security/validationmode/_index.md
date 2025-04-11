---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode 枚举。指定 PDF 签名验证过程的验证模式
type: docs
weight: 10060
url: /zh/net/aspose.pdf.security/validationmode/
---
## ValidationMode 枚举

指定 PDF 签名验证过程的验证模式。

```csharp
public enum ValidationMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 表示不执行验证的模式。 |
| OnlyCheck | `1` | 表示进行验证的模式，但其结果不影响数字签名的验证。您可以自行检查验证结果。 |
| Strict | `2` | 表示进行验证的模式，其结果影响数字签名的验证。如果证书无法验证，则数字签名将被视为无效。您可以自行检查验证结果。 |

### 另请参见

* 命名空间 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* 程序集 [Aspose.PDF](../../)