---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage 枚举。表示文档中数字签名提供的覆盖级别的枚举
type: docs
weight: 10110
url: /zh/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage 枚举

表示文档中数字签名提供的覆盖级别的枚举。

```csharp
public enum SignaturesCoverage
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Undefined | `0` | 表示文档中数字签名的覆盖状态未定义。此值通常在文档中的一个或多个签名被破坏或无法验证时使用，从而阻止对文档签名覆盖的明确评估。 |
| EntirelySigned | `1` | 表示文档完全由数字签名覆盖。此值表示文档的所有必要部分均已签名，并且没有签名被破坏。 |
| PartiallySigned | `2` | 表示文档部分签名，这意味着其内容中的某些部分被数字签名覆盖，但并非全部。此值在文档的某些部分仍未签名或被排除在签名覆盖之外时使用。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* 程序集 [Aspose.PDF](../../)