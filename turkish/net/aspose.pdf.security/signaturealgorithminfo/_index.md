---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.SignatureAlgorithmInfo sınıfı. Bir imza algoritması hakkında bilgi veren bir sınıfı temsil eder; bu, türü, kriptografik standardı ve özet hash algoritmasını içerir.
type: docs
weight: 10000
url: /tr/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo sınıfı

Bir imza algoritması hakkında bilgi veren bir sınıfı temsil eder; bu, türü, kriptografik standardı ve özet hash algoritmasını içerir.

```csharp
public abstract class SignatureAlgorithmInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | İmza alanının adını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Mevcut bilgi nesnesini string temsilime dönüştürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF belgesini imzalamak için kullanılan imza algoritmasının türünü alır. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF belgesini imzalamak için kullanılan kriptografik standardı alır. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | İmza için kullanılan özet hash algoritmasını alır. Bir zaman damgası için, bu, belgenin içeriğinin hash'inin imzalandığı özet hash algoritmasıdır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)