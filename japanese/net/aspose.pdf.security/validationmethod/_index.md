---
title: "列挙体 ValidationMethod"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Security.ValidationMethod 列挙体。証明書検証に使用される方法を定義した列挙体を表します。"
type: docs
weight: 10230
url: /ja/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

証明書検証に使用される方法を定義した列挙型を表します。

```csharp
public enum ValidationMethod
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | 証明書検証の最適な方法を自動的に決定します。 |
| Ocsp | `1` | 証明書検証にオンライン証明書ステータスプロトコル（OCSP）を使用します。OCSP は、発行元認証局（CA）に直接問い合わせることで証明書の検証ステータスを提供するプロトコルです。 |
| Crl | `2` | 証明書失効リスト（CRL）方式を使用して証明書を検証します。 |
| All | `3` | 証明書の検証のために利用可能なすべての方法（OCSP と CRL）を使用します。 |

### 関連項目

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


