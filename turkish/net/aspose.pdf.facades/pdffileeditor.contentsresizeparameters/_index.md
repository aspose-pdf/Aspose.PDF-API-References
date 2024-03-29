---
title: PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Referansı
description: Sayfa yeniden boyutlandırma parametrelerini belirtmek için sınıf. Aşağıdaki parametreleri ayarlamaya izin verin Varsayılan alan birimlerinde veya ilk sayfa boyutunun yüzdelerinde sonuç sayfasının boyutu genişlik yükseklik Varsayılan boşluk birimlerinde veya ilk sayfa boyutunun yüzdelerinde Sol Üst Alt ve Sağ kenar boşlukları Otomatik hesaplama için bazı değerler boş bırakılabilir. Bu değerler açıkça belirtilen değerlerin hesaplanmasından sonra sayfa boyutunun geri kalanından olarak hesaplanacaktır. Örneğin eğer sayfa genişliği  100 ve yeni sayfa genişliği 60 birim olarak belirlenmişse sol ve sağ kenar boşlukları otomatik olarak hesaplanır 100 - 60 / 2  15. Bu sınıf ResizeContents yönteminde kullanılır.
type: docs
weight: 2490
url: /tr/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Sayfa yeniden boyutlandırma parametrelerini belirtmek için sınıf. Aşağıdaki parametreleri ayarlamaya izin verin: Varsayılan alan birimlerinde veya ilk sayfa boyutunun yüzdelerinde sonuç sayfasının boyutu (genişlik, yükseklik); Varsayılan boşluk birimlerinde veya ilk sayfa boyutunun yüzdelerinde Sol, Üst, Alt ve Sağ kenar boşlukları; Otomatik hesaplama için bazı değerler boş bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfa boyutunun geri kalanından olarak hesaplanacaktır. Örneğin: eğer sayfa genişliği = 100 ve yeni sayfa genişliği 60 birim olarak belirlenmişse, sol ve sağ kenar boşlukları otomatik olarak hesaplanır: (100 - 60) / 2 = 15. Bu sınıf ResizeContents yönteminde kullanılır.

```csharp
public class ContentsResizeParameters
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ContentsResizeParameters](contentsresizeparameters#constructor)() | Tüm değerlerin "otomatik" olarak ayarlandığı yeniden boyutlandırma parametreleri oluşturur. Gerekirse daha sonraki kenar boşlukları ve içerik boyutu belirtilebilir. |
| [ContentsResizeParameters](contentsresizeparameters#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Belirtilen kenar boşluğu değerleri ve içerik boyutu ile yeniden boyutlandırma parametreleri oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/contentsresizeparameters/bottommargin) { get; set; } | Ortaya çıkan sayfada alt kenar boşluğunu alır veya ayarlar. |
| [ContentsHeight](../../aspose.pdf.facades/contentsresizeparameters/contentsheight) { get; set; } | Elde edilen sayfadaki kaynak sayfanın içeriğinin yüksekliğini alır veya ayarlar. |
| [ContentsWidth](../../aspose.pdf.facades/contentsresizeparameters/contentswidth) { get; set; } | Sonuç sayfasındaki kaynak sayfanın içeriğinin genişliğini alır veya ayarlar. |
| [LeftMargin](../../aspose.pdf.facades/contentsresizeparameters/leftmargin) { get; set; } | Sonuç sayfasında sol kenar boşluğunu alır veya ayarlar. |
| [RightMargin](../../aspose.pdf.facades/contentsresizeparameters/rightmargin) { get; set; } | Sonuç sayfasında sağ kenar boşluğunu alır veya ayarlar. |
| [TopMargin](../../aspose.pdf.facades/contentsresizeparameters/topmargin) { get; set; } | Sonuç sayfasında üst kenar boşluğunu alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/contentsresizeparameters/contentsize)(double, double) | Belirtilen içerik boyutuyla yeniden boyutlandırma parametreleri oluşturur. |
| static [ContentSizePercent](../../aspose.pdf.facades/contentsresizeparameters/contentsizepercent)(double, double) | İlk sayfa boyutunun yüzdeleri olarak belirtilen içerik boyutuyla yeniden boyutlandırma parametreleri oluşturur. Kenar boşlukları otomatik olarak hesaplanır. |
| static [Margins](../../aspose.pdf.facades/contentsresizeparameters/margins)(double, double, double, double) | Belirtilen kenar boşlukları değeriyle yeniden boyutlandırma parametreleri oluşturur. İçerik boyutu otomatik olarak hesaplanır. |
| static [MarginsPercent](../../aspose.pdf.facades/contentsresizeparameters/marginspercent)(double, double, double, double) | Yeniden boyutlandırma parametreleri oluşturur. Kenar boşlukları, ilk sayfa boyutunun yüzdeleri olarak belirtilir. |
| static [PageResize](../../aspose.pdf.facades/contentsresizeparameters/pageresize)(double, double) | Sayfa yeniden boyutlandırma için yeniden boyutlandırma parametreleri oluşturur. |
| static [PageResizePct](../../aspose.pdf.facades/contentsresizeparameters/pageresizepct)(double, double) | Sayfa yeniden boyutlandırma için yeniden boyutlandırma parametreleri oluşturur. Yeni boyutlar yüzde olarak belirtilir. |

### Ayrıca bakınız

* class [PdfFileEditor](../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
