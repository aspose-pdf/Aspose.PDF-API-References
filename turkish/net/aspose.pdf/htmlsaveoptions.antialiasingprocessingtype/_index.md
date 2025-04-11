---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType enum. Bu enum, dönüştürme sırasında olası kenar yumuşatma önlemlerini tanımlar.
type: docs
weight: 5570
url: /tr/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumerasyonu

Bu enum, dönüştürme sırasında olası kenar yumuşatma önlemlerini tanımlar.

```csharp
public enum AntialiasingProcessingType
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | özel bir kenar yumuşatma işlemi kullanılmamaktadır. Bu, belgelerin büyük çoğunluğu için optimal bir seçenektir ve dönüştürme sırasında ek zaman gerektirmez. |
| TryCorrectResultHtml | `1` | Bu durumda, dönüştürücü, bitişik arka plan grafik öğeleri ile yerleri tespit etmeye ve ilgili şekilde sonuç HTML'sini düzeltmeye çalışır. Bu seçenek, birden fazla bitişik grafik öğeden oluşan arka planlar içeren belgeler için dışa aktarma sonucunu geliştirmeye olanak tanır (bu tür belgeler için PDF render'ları, örneğin Acrobat Reader, genellikle render sırasında öğelerin sınırlarını yumuşatmaya çalışır. Bu seçenek, dönüştürücünün PDF render'larının bu davranışını taklit etmesine olanak tanır. Bu seçenek, bazı belirli belgelerin (bu tür bileşik arka planlar kullanan) dışa aktarma sonucunun düzenini geliştirmeye olanak tanır, ancak işlem için ek zaman gerektirir (genellikle ek zamanın yaklaşık %10-15'i kadar). Bu nedenle, bu modun genel durumda kullanılması önerilmez. |

### Ayrıca Bakınız

* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)