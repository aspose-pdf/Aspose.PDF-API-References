---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod 列挙型。証明書検証に使用されるメソッドを定義した列挙型を表します。
type: docs
weight: 10050
url: /ja/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod 列挙型

証明書検証に使用されるメソッドを定義した列挙型を表します。

```csharp
public enum ValidationMethod
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | 証明書検証に最適なメソッドを自動的に決定します。 |
| Ocsp | `1` | 証明書検証にオンライン証明書状態プロトコル (OCSP) を使用します。OCSP は、発行元の証明書機関 (CA) に直接問い合わせることで証明書の検証状況を提供するプロトコルです。 |
| Crl | `2` | 証明書失効リスト (CRL) メソッドを使用して証明書を検証します。 |
| All | `3` | 証明書検証に利用可能なすべてのメソッド (OCSP と CRL) を使用します。 |

### 参照

* 名前空間 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* アセンブリ [Aspose.PDF](../../)