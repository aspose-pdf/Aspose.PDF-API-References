---
title: HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Referansı
description: Bu numaralandırma convert sırasında olası kenar yumuşatma önlemlerini açıklar
type: docs
weight: 3440
url: /tr/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Bu numaralandırma, convert sırasında olası kenar yumuşatma önlemlerini açıklar

```csharp
public enum AntialiasingProcessingType
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | kullanımda özel bir kenar yumuşatma işlemi yok. Bu, belgelerin büyük çoğunluğunun üstesinden gelmek için en uygun seçeneğidir ve dönüştürme sırasında ek zaman gerektirmez |
| TryCorrectResultHtml | `1` | Böyle bir durumda dönüştürücü, bitişik arka plan grafik öğelerine sahip yerleri algılamaya çalışır ve uygun şekilde sonuç HTML'sini düzeltmeye çalışır. Bu seçenek, birkaç bitişik grafik öğeden oluşturulmuş arka planlar içeren belgeler için dışa aktarma sonucunun iyileştirilmesine izin verir (bu tür belgeler için PDF oluşturucular) , fe Acrobat Reader, oluşturma sırasında genellikle öğelerin sınırlarını düzgün bir şekilde dener. Bu seçenekle dönüştürücü, PDF oluşturucuların bu davranışını taklit eder. Bu seçenek, bazı belirli belgeler (bu tür bileşik arka planları kullanan) için dışa aktarma sonucunun düzenini iyileştirmeye izin verir, ancak işlem için ek süre gerektirir (genellikle ek sürenin yaklaşık %10-15'i kadar). Bu nedenle genel durumda bu modun kullanılması önerilmez. |

### Ayrıca bakınız

* class [HtmlSaveOptions](../htmlsaveoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
