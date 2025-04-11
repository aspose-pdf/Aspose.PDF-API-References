---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes enum. DİKKAT Uygulanan özellik ancak örnek belgede ortaya çıkan OSHARED katmanındaki engelleyici sorun nedeniyle henüz kamu API'sine eklenmedi. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB gibi formatlar genellikle akışkan tasarıma sahiptir, bu nedenle gerekli sayfa boyutuna uyum sağlar. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilmesine izin vermeyen belirli yatay konumlar veya boyutlar içerir. Bu durumda, içerik boyutunun sonuç PDF belgesinin gerekli başlangıç sayfa boyutuna uymadığı durumlarda ne yapılması gerektiğini tanımlayabiliriz.
type: docs
weight: 6140
url: /tr/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumerasyonu

DİKKAT! Uygulanan özellik ancak örnek belgede ortaya çıkan OSHARED katmanındaki engelleyici sorun nedeniyle henüz kamu API'sine eklenmedi. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. Formatlar (HTML, EPUB vb. gibi), genellikle akışkan tasarıma sahiptir, bu nedenle gerekli sayfa boyutuna uyum sağlar. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilmesine izin vermeyen belirli yatay konumlar veya boyutlar içerir. Bu durumda, içerik boyutunun sonuç PDF belgesinin gerekli başlangıç sayfa boyutuna uymadığı durumlarda ne yapılması gerektiğini tanımlayabiliriz.

```csharp
public enum PageSizeAdjustmentModes
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | Bu modda sonuç sayfaları, dönüşüm sonrası içeriğin sayfa sınırlarını aşıp aşmadığına bakılmaksızın, LoadOptions'da tanımlanan gerekli sayfa boyutuna sahip olacaktır. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Bu mod, dönüşüm sonucunun alınmasından sonra bazı içeriklerin kesildiğinin tespit edilmesi durumunda, içerik sığdırmak için portview genişletilir ve dönüşüm tekrarlanır. Bu mod, böyle bir durumda sonuçta daha az sayfa elde edilmesine olanak tanır ancak tekrar render almayı (ve dolayısıyla daha fazla işlem süresi) gerektirir. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)