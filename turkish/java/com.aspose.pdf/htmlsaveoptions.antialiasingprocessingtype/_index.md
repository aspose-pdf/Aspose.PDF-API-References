---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu enum, dönüşüm sırasında olası antialiasing önlemlerini tanımlar"
type: docs
weight: 2000
url: /tr/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Bu enum, dönüşüm sırasında olası antialiasing önlemlerini tanımlar

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Kullanılan özel bir anti-alias işleme yoktur. Bu, belgelerin büyük çoğunluğu için optimal bir seçenektir ve dönüşüm sırasında ek zaman gerektirmez. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | Bu durumda dönüştürücü, bitişik arka plan grafik öğelerinin bulunduğu yerleri tespit etmeye ve sonuç HTML'yi ilgili şekilde düzeltmeye çalışır. Bu seçenek, birkaç bitişik grafik öğeden oluşan arka planları içeren belgeler için dışa aktarma sonucunu iyileştirmeyi sağlar (bu tür belgelerde PDF renderers, f.e. Acrobat Reader, genellikle öğelerin sınırlarını renderleme sırasında yumuşatmaya çalışır. Bu seçenekle dönüştürücü, PDF-renderers'in bu davranışını taklit eder. Bu seçenek, birleşik arka planları kullanan bazı belirli belgeler için dışa aktarma düzenini iyileştirir, ancak işlem için ek zaman gerektirir (genellikle ek zamanın yaklaşık %10‑15'i). Bu modun genel durumda kullanımı önerilmez. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Kullanılan özel bir anti-alias işleme yoktur. Bu, belgelerin büyük çoğunluğu için optimal bir seçenektir ve dönüşüm sırasında ek zaman gerektirmez.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

Bu durumda dönüştürücü, bitişik arka plan grafik öğelerinin bulunduğu yerleri tespit etmeye ve sonuç HTML'yi ilgili şekilde düzeltmeye çalışır. Bu seçenek, birkaç bitişik grafik öğeden oluşan arka planları içeren belgeler için dışa aktarma sonucunu iyileştirmeyi sağlar (bu tür belgelerde PDF renderers, f.e. Acrobat Reader, genellikle öğelerin sınırlarını renderleme sırasında yumuşatmaya çalışır. Bu seçenekle dönüştürücü, PDF-renderers'in bu davranışını taklit eder. Bu seçenek, birleşik arka planları kullanan bazı belirli belgeler için dışa aktarma düzenini iyileştirir, ancak işlem için ek zaman gerektirir (genellikle ek zamanın yaklaşık %10‑15'i). Bu modun genel durumda kullanımı önerilmez.
