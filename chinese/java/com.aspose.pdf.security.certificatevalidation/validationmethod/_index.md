---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于证书验证的方法的枚举。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

表示用于证书验证的方法的枚举。

## 字段

| 字段 | 描述 |
| --- | --- |
| [All](#All) | 使用所有可用的方法（OCSP 和 CRL）进行证书验证。 |
| [Auto](#Auto) | 自动确定证书验证的最佳方法。 |
| [Crl](#Crl) | 使用证书吊销列表（CRL）方法验证证书。 |
| [Ocsp](#Ocsp) | 使用在线证书状态协议（OCSP）进行证书验证。OCSP 是一种通过直接查询颁发证书的证书颁发机构（CA）来提供证书验证状态的协议。 |

### All {#All}
```
public static final int All
```

使用所有可用的方法（OCSP 和 CRL）进行证书验证。

### Auto {#Auto}
```
public static final int Auto
```

自动确定证书验证的最佳方法。

### Crl {#Crl}
```
public static final int Crl
```

使用证书吊销列表（CRL）方法验证证书。

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

使用在线证书状态协议（OCSP）进行证书验证。OCSP 是一种通过直接查询颁发证书的证书颁发机构（CA）来提供证书验证状态的协议。
