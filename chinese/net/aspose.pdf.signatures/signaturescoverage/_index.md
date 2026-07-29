---
title: "枚举 SignaturesCoverage"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Signatures.SignaturesCoverage 枚举。表示文档中数字签名提供的覆盖级别的枚举"
type: docs
weight: 10290
url: /zh/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

表示文档中数字签名提供的覆盖级别的枚举。

```csharp
public enum SignaturesCoverage
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Undefined | `0` | 指示文档中数字签名覆盖状态未定义。此值通常在文档中一个或多个签名受损或无法验证时使用，导致无法对文档的签名覆盖进行明确评估。 |
| EntirelySigned | `1` | 指示文档已被数字签名完全覆盖。此值表示文档的所有必需部分已签名且没有签名受损。 |
| PartiallySigned | `2` | 指示文档部分签名，这意味着其内容的部分（但不是全部）已被数字签名覆盖。此值在文档的某些部分仍未签名或被排除在签名覆盖范围之外时使用。 |

### 另请参见

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


