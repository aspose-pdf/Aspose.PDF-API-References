---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Dönüşüm sonucu bir veya birkaç HTML‑sayfası ( aynı zamanda resim veya yazı tipi gibi dış dosyalara başvurabilir) içerebilir. Bu özelliğe, oluşturulan bir temsilci atayabilirsiniz."
type: docs
weight: 2110
url: /tr/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Dönüşüm sonucu bir veya birkaç HTML sayfası (görüntüler veya yazı tipleri gibi harici dosyalara da başvurabilir) içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan HTML sayfasının (HTML'in kendisinin) işlenmesini uygulayan özel bir yöntemden oluşturulan temsilciyi atayabilirsiniz. Bu durumda işleme (akışa veya diske kaydetme gibi) o özel kod içinde yapılabilir. Bu durumda, HTML sayfasının işaretlemesinin kaydedilmesi için gerekli tüm eylemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü dönüştürücünün kodundaki kaydetme kullanılmayacaktır. Eğer bu veya o durum için işleme bir sebeple dönüştürücünün kodu tarafından, özel kod yerine yapılması gerekiyorsa, lütfen özel kod içinde 'htmlSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların, dışsal bir özel kaydetme kodu yokmuş gibi, dönüştürücü içinde yapılması gerektiğini bildirir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Dahili beginInvoke yöntemi |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Dahili endInvoke yöntemi |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Çağrılan yöntem |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Dahili beginInvoke yöntemi

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Dahili endInvoke yöntemi

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Çağrılan yöntem
