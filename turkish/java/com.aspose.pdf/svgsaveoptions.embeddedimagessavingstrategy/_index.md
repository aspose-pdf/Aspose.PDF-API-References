---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu tür bir To özelliğine, PDF'den oluşturulan SVG'den çıkarılan görüntünün harici kaydedilmesini işleyen özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz."
type: docs
weight: 4730
url: /tr/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Bu tür bir özelliğe, PDF'den oluşturulan SVG'den çıkarılan ve PDF'den HTML'ye dönüştürme sırasında harici bir kaynak olarak kaydedilmesi gereken görüntünün dışa kaydedilmesini işleyen özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Böyle bir durumda, (akışa veya diske kendi yapmış olduğunuz kaydetme gibi) işleme, o özel kod içinde yapılabilir ve bu özel kod, daha sonra oluşturulan SVG'ye orijinal varsayılan görüntü kaynağı yolunun yerine eklenecek yolu (veya tırnak işareti olmayan başka bir dize) döndürmelidir. Bu durumda, görüntünün kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda yapılmalıdır, çünkü dönüştürücünün kodundaki kaydetme kullanılmayacaktır. Eğer bu ya da o dosyanın işlenmesi bir sebeple dönüştürücünün kodu tarafından, özel kodda değil yapılmalıysa, lütfen özel kod içinde 'imageSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dış bir özel kod olmadığı gibi dönüştürücü içinde yapılması gerektiğini bildirir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
