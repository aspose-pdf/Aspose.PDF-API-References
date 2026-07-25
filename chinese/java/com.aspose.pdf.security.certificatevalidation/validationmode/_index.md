---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Aspose.PDF for Java API 参考"
description: "指定 PDF 签名验证过程的验证模式。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

指定 PDF 签名验证过程的验证模式。

## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 表示未执行验证的模式。 |
| [OnlyCheck](#OnlyCheck) | 表示进行验证的模式，但其结果不影响数字签名的验证。您可以自行检查验证结果。 |
| [Strict](#Strict) | 表示进行验证的模式且其结果影响数字签名的验证。如果证书无法验证，则数字签名将被视为无效。您可以自行检查验证结果。 |

### None {#None}
```
public static final int None
```

表示未执行验证的模式。

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

表示进行验证的模式，但其结果不影响数字签名的验证。您可以自行检查验证结果。

### Strict {#Strict}
```
public static final int Strict
```

表示进行验证的模式且其结果影响数字签名的验证。如果证书无法验证，则数字签名将被视为无效。您可以自行检查验证结果。
