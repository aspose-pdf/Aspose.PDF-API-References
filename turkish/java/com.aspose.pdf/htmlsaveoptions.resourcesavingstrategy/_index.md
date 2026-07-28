---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu özelliğe, PDF'ten çıkarılan ve kaydedilmesi gereken harici kaynak (Yazı tipi veya Görüntü) işleme uygulayan özel bir yöntemden oluşturulan delegeyi atayabilirsiniz."
type: docs
weight: 2150
url: /tr/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Bu özelliğe, PDF'den çıkarılan ve PDF'den HTML'ye dönüşüm sırasında harici kaynak olarak kaydedilmesi gereken dış kaynağın (Yazı tipi veya Görüntü) işlenmesini uygulayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Böyle bir durumda işleme (akışa veya diske kaydetme gibi) bu özel kod içinde yapılabilir ve bu özel kod, daha sonra oluşturulan HTML'ye, o görüntü kaynağına ait orijinal varsayılan yol yerine dahil edilecek yolu (veya tırnak işareti olmayan başka bir dizeyi) döndürmelidir. Bu durumda görüntünün kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda yapılmalıdır, çünkü dönüştürücünün kodunda sonucun kaydedilmesi kullanılmayacaktır. Eğer bu veya o dosyanın işlenmesi bir sebeple dönüştürücünün kodu tarafından, özel kod yerine yapılması gerekiyorsa, lütfen özel kod içinde 'CustomProcessingCancelled' bayrağını 'resourceSavingInfo' parametresinin değişkenine ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların, dış bir özel kod yokmuş gibi, dönüştürücü içinde yapılması gerektiğini bildirir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Çağrılan yöntem |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Çağrılan yöntem
