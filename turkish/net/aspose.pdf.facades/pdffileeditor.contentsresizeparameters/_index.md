---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters sınıfı. Sayfa yeniden boyutlandırma parametrelerini belirtmek için sınıf. Aşağıdaki parametrelerin ayarlanmasına izin verir: Sonuç sayfasının boyutu varsayılan alan birimlerinde veya başlangıç sayfalarının boyutunun yüzdesi olarak; Sol, Üst, Alt ve Sağ kenar boşlukları varsayılan alan birimlerinde veya başlangıç sayfasının boyutunun yüzdesi olarak; Bazı değerler otomatik hesaplama için boş bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfa boyutunun geri kalanından hesaplanacaktır. Bu sınıf, ResizeContents yönteminde kullanılır.
type: docs
weight: 4480
url: /tr/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters sınıfı

Sayfa yeniden boyutlandırma parametrelerini belirtmek için sınıf. Aşağıdaki parametrelerin ayarlanmasına izin verir: Sonuç sayfasının boyutu (genişlik, yükseklik) varsayılan alan birimlerinde veya başlangıç sayfalarının boyutunun yüzdesi olarak; Sol, Üst, Alt ve Sağ kenar boşlukları varsayılan alan birimlerinde veya başlangıç sayfasının boyutunun yüzdesi olarak; Bazı değerler otomatik hesaplama için boş bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfa boyutunun geri kalanından hesaplanacaktır. Örneğin: sayfa genişliği = 100 ve yeni sayfa genişliği 60 birim olarak belirtilirse, sol ve sağ kenar boşlukları otomatik olarak hesaplanır: (100 - 60) / 2 = 15. Bu sınıf, ResizeContents yönteminde kullanılır.

```csharp
public class ContentsResizeParameters
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Tüm değerlerin "otomatik" olarak ayarlandığı yeniden boyutlandırma parametrelerini oluşturur. Daha sonra gerekirse kenar boşlukları ve içerik boyutu belirtilebilir. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Belirtilen kenar boşluğu değerleri ve içerik boyutu ile yeniden boyutlandırma parametrelerini oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Sonuç sayfasındaki alt kenar boşluğunu alır veya ayarlar. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Sonuç sayfasındaki kaynak sayfanın içeriğinin yüksekliğini alır veya ayarlar. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Sonuç sayfasındaki kaynak sayfanın içeriğinin genişliğini alır veya ayarlar. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Sonuç sayfasındaki sol kenar boşluğunu alır veya ayarlar. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Sonuç sayfasındaki sağ kenar boşluğunu alır veya ayarlar. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Sonuç sayfasındaki üst kenar boşluğunu alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Belirtilen içerik boyutları ile yeniden boyutlandırma parametrelerini oluşturur. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Başlangıç sayfa boyutunun yüzdesi olarak belirtilen içerik boyutları ile yeniden boyutlandırma parametrelerini oluşturur. Kenar boşlukları otomatik olarak hesaplanır. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Belirtilen kenar boşluğu değerleri ile yeniden boyutlandırma parametrelerini oluşturur. İçerik boyutu otomatik olarak hesaplanır. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Yeniden boyutlandırma parametrelerini oluşturur. Kenar boşlukları başlangıç sayfa boyutunun yüzdesi olarak belirtilir. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Sayfa yeniden boyutlandırma için parametreleri oluşturur. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Sayfa yeniden boyutlandırma için parametreleri oluşturur. Yeni boyutlar yüzde olarak belirtilir. |

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../pdffileeditor/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)