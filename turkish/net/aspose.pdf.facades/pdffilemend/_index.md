---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend sınıfı. Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder.
type: docs
weight: 4530
url: /tr/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend Sınıfı

Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Yapıcı. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | *belge* temelinde yeni bir `PdfFileMend` nesnesi başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | AddText yöntemlerinde kelime sarma durumunu belirten bir bool değeri ayarlar. Değer true ise, FormattedText içindeki metin kelime sarar. Varsayılan olarak, değer false'dur. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Metin konumlandırma stratejisini ayarlar veya alır. [`PositioningMode`](../positioningmode/) Varsayılan mod Legacy'dir. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Kelime sarma algoritmasını ayarlar veya alır. WordWrapMode ve IsWordWrap'a bakın. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Uygulanmadı. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Uygulanmadı. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Uygulanmadı. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | PdfFileMend nesnesini kapatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | PDF belgesini belirtilen dosyaya kaydeder. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)