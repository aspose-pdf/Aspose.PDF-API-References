---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions sınıfı. PDF belgesine SVG dosyasını yüklemek/içeri aktarmak için seçenekleri temsil eder.
type: docs
weight: 10210
url: /tr/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions sınıfı

PDF belgesine SVG dosyasını yüklemek/içeri aktarmak için seçenekleri temsil eder.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | PDF sayfa boyutunu SVG boyutuna ayarlayın |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosya yüklenirken tüm fontlar için lisans kısıtlamalarını devre dışı bırakacak bayrağı alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir; örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan olarak `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Belge yüklenirken uygulanması gereken sayfa bilgilerini alır veya ayarlar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir; bu durumda yükleme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Dönüşüm sırasında kullanılacak dönüşüm motorunu seçmenizi sağlar. Şu anda yeni motor B-test aşamasındadır, bu nedenle bu değer varsayılan olarak ConversionEngines.LegacyEngine olarak ayarlanmıştır. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)