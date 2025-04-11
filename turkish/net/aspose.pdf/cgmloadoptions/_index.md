---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions sınıfı. CGM dosyasını pdf belgesine yüklemek/içeri aktarmak için seçenekler içerir
type: docs
weight: 3010
url: /tr/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions Sınıfı

CGM dosyasını pdf belgesine yüklemek/içeri aktarmak için seçenekler içerir.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | CGM dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Tanımlı !:pageSize ile yükleme seçenekleri oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemleri gerçekleştirmeye izin verir, örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontu PDF belgesine gömmeye izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | İçe aktarma için çıktı sayfa boyutunu alır veya ayarlar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir; bu durumda yükleme işlemi durmalıdır. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)