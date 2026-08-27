---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "証明書検証に使用される方法を定義した列挙型を表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

証明書検証に使用される方法を定義した列挙型を表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [All](#All) | 証明書検証に利用可能なすべての方法（OCSP と CRL）を使用します。 |
| [Auto](#Auto) | 証明書の検証に最適な方法を自動的に決定します。 |
| [Crl](#Crl) | 証明書失効リスト（CRL）方式を使用して証明書を検証します。 |
| [Ocsp](#Ocsp) | 証明書の検証にオンライン証明書ステータスプロトコル（OCSP）を使用します。OCSP は、発行元認証局（CA）に直接問い合わせることで証明書の検証ステータスを提供するプロトコルです。 |

### All {#All}
```
public static final int All
```

証明書検証に利用可能なすべての方法（OCSP と CRL）を使用します。

### Auto {#Auto}
```
public static final int Auto
```

証明書の検証に最適な方法を自動的に決定します。

### Crl {#Crl}
```
public static final int Crl
```

証明書失効リスト（CRL）方式を使用して証明書を検証します。

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

証明書の検証にオンライン証明書ステータスプロトコル（OCSP）を使用します。OCSP は、発行元認証局（CA）に直接問い合わせることで証明書の検証ステータスを提供するプロトコルです。
