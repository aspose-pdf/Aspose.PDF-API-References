---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CdrLoadOptions sınıfı. Sınıf CDR yükleme seçeneklerini tanımlar
type: docs
weight: 2960
url: /tr/net/aspose.pdf/cdrloadoptions/
---
## CdrLoadOptions sınıfı

Sınıf CDR yükleme seçeneklerini tanımlar.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansının yasakladığı fontlarla işlemler gerçekleştirilmesine izin verir, örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam et veya iptal et belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal de döndürebilir; bu durumda yükleme işlemi durmalıdır. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)