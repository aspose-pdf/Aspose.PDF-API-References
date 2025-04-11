---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsLoadOptions sınıfı. .mht dosyasının pdf belgesine yüklenmesi/içeri aktarılması için seçenekleri temsil eder
type: docs
weight: 9730
url: /tr/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions Sınıfı

.mht dosyasının pdf belgesine yüklenmesi/içeri aktarılması için seçenekleri temsil eder.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosya yüklenirken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir; örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Font klasörlerinin yollarını alır veya ayarlar. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal etmeyi de döndürebilir; bu durumda yükleme işlemi durmalıdır. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)