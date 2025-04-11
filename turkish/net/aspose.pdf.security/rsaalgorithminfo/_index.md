---
title: Class RsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.RsaAlgorithmInfo sınıfı. RSA imza algoritması hakkında bilgi için bir sınıfı temsil eder
type: docs
weight: 9990
url: /tr/net/aspose.pdf.security/rsaalgorithminfo/
---
## RsaAlgorithmInfo sınıfı

RSA imza algoritması hakkında bilgi için bir sınıfı temsil eder.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | İmza alanının adını alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Mevcut bilgi nesnesini string temsilime dönüştürür. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF belgesini imzalamak için kullanılan imza algoritmasının türünü alır. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF belgesini imzalamak için kullanılan kriptografik standardı alır. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | İmza için kullanılan özet hash algoritmasını alır. Bir zaman damgası için, bu belgenin içeriğinin hash'inin imzalandığı özet hash algoritmasıdır. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | İmza algoritması tarafından kullanılan kriptografik anahtarın boyutunu alır. |

### Ayrıca Bakınız

* sınıf [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* ad alanı [Aspose.Pdf.Security](../../aspose.pdf.security/)
* derleme [Aspose.PDF](../../)