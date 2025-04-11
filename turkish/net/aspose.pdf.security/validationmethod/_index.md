---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod enum. Sertifika doğrulama için kullanılan yöntemi tanımlayan bir enum'u temsil eder.
type: docs
weight: 10050
url: /tr/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumerasyonu

Sertifika doğrulama için kullanılan yöntemi tanımlayan bir enum'u temsil eder.

```csharp
public enum ValidationMethod
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Sertifika doğrulama için en iyi yöntemi otomatik olarak belirler. |
| Ocsp | `1` | Sertifika doğrulama için Çevrimiçi Sertifika Durum Protokolü (OCSP) kullanır. OCSP, bir sertifikanın doğrulama durumunu doğrudan veren Sertifika Otoritesi'ni (CA) sorgulayarak sağlayan bir protokoldür. |
| Crl | `2` | Sertifikaları Sertifika İptal Listesi (CRL) yöntemi ile doğrular. |
| All | `3` | Sertifika doğrulama için mevcut tüm yöntemleri (OCSP ve CRL) kullanır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)