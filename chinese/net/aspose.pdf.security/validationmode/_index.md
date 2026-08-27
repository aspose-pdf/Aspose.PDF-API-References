---
title: "枚举 ValidationMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Security.ValidationMode 枚举。指定 PDF 签名验证过程的验证模式"
type: docs
weight: 10240
url: /zh/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

指定 PDF 签名验证过程的验证模式。

```csharp
public enum ValidationMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 表示未执行验证的模式。 |
| OnlyCheck | `1` | 表示进行验证的模式，但其结果不影响数字签名的验证。您可以自行检查验证结果。 |
| Strict | `2` | 表示进行验证的模式且其结果会影响数字签名的验证。如果证书无法验证，则数字签名将被视为无效。您可以自行检查验证结果。 |

### 另请参见

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


