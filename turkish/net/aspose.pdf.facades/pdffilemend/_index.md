---
title: PdfFileMend
second_title: Aspose.PDF for .NET API Referansı
description: Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder.
type: docs
weight: 2540
url: /tr/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileMend](pdffilemend#constructor)() | Yapıcı. |
| [PdfFileMend](pdffilemend#constructor_1)(Document) | Yeniyi başlatır[`PdfFileMend`](../pdffilemend) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap) { set; } | AddText yöntemlerinde sözcük kaydırmayı belirten bir bool değeri ayarlar. Değer doğruysa, FormattedText içindeki metin sözcük kaydırır. Varsayılan olarak değer false'tur. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode) { get; set; } | Metin konumlandırma stratejisini ayarlar veya alır.[`PositioningMode`](../positioningmode) Varsayılan mod Eski'dir. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode) { get; set; } | Sözcük kaydırma algoritmasını ayarlar veya alır. WordWrapMode ve IsWordWrap. 'ye bakın |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage)(Stream, int, float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_2)(Stream, int[], float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_4)(string, int, float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_6)(string, int[], float, float, float, float) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext#addtext)(FormattedText, int, float, float) | Uygulanmadı. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext#addtext_1)(FormattedText, int, float, float, float, float) | Uygulanmadı. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext#addtext_2)(FormattedText, int[], float, float, float, float) | Uygulanmadı. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close)() | PdfFileMend nesnesini kapatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save#save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save#save_1)(string) | PDF belgesini belirtilen dosyaya kaydeder. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->