---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer sınıfı. PDF belgelerini grafiksel olarak karşılaştırmak için bir sınıfı temsil eder. Öncelikle grafiksel nitelikteki küçük değişiklikleri aramak için kullanılmalıdır. Metin içeriği değişikliklerini karşılaştırmak için diğer PDF karşılaştırma sınıflarını kullanın.
type: docs
weight: 3190
url: /tr/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer sınıfı

PDF belgelerini grafiksel olarak karşılaştırmak için bir sınıfı temsil eder. Öncelikle grafiksel nitelikteki küçük değişiklikleri aramak için kullanılmalıdır. Metin içeriği değişikliklerini karşılaştırmak için diğer PDF karşılaştırma sınıflarını kullanın.

```csharp
public class GraphicalPdfComparer
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Değişiklik bayrağı rengini alır ve ayarlar. Varsayılan renk kırmızıdır. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Ortaya çıkan görüntülerin çözümünü alır ve ayarlar. Varsayılan değer 150dpi'dir. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Yüzde cinsinden eşik değerini alır ve ayarlar. Bu değer, sizin için önemli değilse küçük değişiklikleri göz ardı etmenizi sağlar. Varsayılan değer %0'dır. |

## Metodlar

| İsim | Açıklama |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Belgeleri grafiksel olarak karşılaştırır. Karşılaştırma sonucu görüntülere yerleştirilir. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Belgeleri grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir görüntüye yerleştirilir. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Sayfalar arasındaki farkları alır. Sonuç, karşılaştırılan ilk sayfanın bir görüntüsünü ve bir farklar dizisini içerir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)