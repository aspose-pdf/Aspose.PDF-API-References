---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptions sınıfı. LoadOptions türü, bireysel yükleme seçenekleri üzerinde soyutlama seviyesini tutar
type: docs
weight: 6120
url: /tr/net/aspose.pdf/loadoptions/
---
## LoadOptions sınıfı

LoadOptions türü, bireysel yükleme seçenekleri üzerinde soyutlama seviyesini tutar

```csharp
public abstract class LoadOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakacak bir bayrak alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir; örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan olarak `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `LoadOptions`'ın tanımladığı dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam et veya durdurma belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir; bu durumda yükleme işlemi durmalıdır. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)