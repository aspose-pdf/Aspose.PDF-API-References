---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文档中数字签名提供的覆盖级别的枚举。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

表示文档中数字签名提供的覆盖级别的枚举。

## 字段

| 字段 | 描述 |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | 指示文档已被数字签名完全覆盖。此值表示文档的所有必需部分均已签名且没有签名受损。 |
| [PartiallySigned](#PartiallySigned) | 指示文档部分签名，这意味着文档的某些内容（但不是全部）已被数字签名覆盖。当文档的某些部分仍未签名或被排除在签名覆盖范围之外时使用此值。 |
| [Undefined](#Undefined) | 指示文档中数字签名覆盖状态未定义。通常在文档中一个或多个签名受损或无法验证时使用此值，从而无法对签名覆盖进行明确评估。 |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

指示文档已被数字签名完全覆盖。此值表示文档的所有必需部分均已签名且没有签名受损。

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

指示文档部分签名，这意味着文档的某些内容（但不是全部）已被数字签名覆盖。当文档的某些部分仍未签名或被排除在签名覆盖范围之外时使用此值。

### Undefined {#Undefined}
```
public static final int Undefined
```

指示文档中数字签名覆盖状态未定义。通常在文档中一个或多个签名受损或无法验证时使用此值，从而无法对签名覆盖进行明确评估。
