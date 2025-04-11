---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.TimestampAlgorithmInfo sınıfı. Zaman damgası imza algoritması hakkında bilgi için bir sınıfı temsil eder
type: docs
weight: 10030
url: /tr/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo sınıfı

Zaman damgası imza algoritması hakkında bilgi için bir sınıfı temsil eder.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | İmza alanının adını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Mevcut bilgi nesnesini string temsilimine dönüştürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF belgesini imzalamak için kullanılan imza algoritmasının türünü alır. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Belgenin içeriğini hashleyen ve ardından [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/) kullanarak imzalayan hash algoritmasını alır. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF belgesini imzalamak için kullanılan kriptografik standardı alır. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | İmza için kullanılan digest hash algoritmasını alır. Bir zaman damgası için, bu belgenin içeriğinin hash'inin imzalandığı digest hash algoritmasıdır. |

### Ayrıca Bakınız

* sınıf [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* ad alanı [Aspose.Pdf.Security](../../aspose.pdf.security/)
* derleme [Aspose.PDF](../../)