---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfPageStamp sınıfı. Sınıf, PDF sayfasını damga olarak kullanan bir damgayı temsil eder.
type: docs
weight: 8420
url: /tr/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp sınıfı

Sınıf, PDF sayfasını damga olarak kullanan bir damgayı temsil eder.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | PdfPageStamp'ın yapıcısı. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Akıştan belgede belirtilen sayfadan PDF sayfa damgası oluşturur. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Belirtilen dosyadaki belgenin belirtilen sayfasından PDF sayfa damgası oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | İçeriğin arka plan olarak damgalanıp damgalanmadığını belirten bir bool değeri ayarlar veya alır. Değer true ise, damga içeriği en altta yer alır. Varsayılan olarak, değer false'tur, damga içeriği en üstte yer alır. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Damganın alt kenar boşluğunu alır veya ayarlar. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Sayfadaki damganın istenen yüksekliği. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Sayfadaki damganın yatay hizalamasını alır veya ayarlar. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Damganın sol kenar boşluğunu alır veya ayarlar. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Damga opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan olarak değer 1.0'dır. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Damga dış hat opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan olarak değer 1.0'dır. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Damga dış hat genişliğinin değerini alır veya ayarlar. Varsayılan olarak değer 1.0'dır. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Damga olarak kullanılacak sayfayı alır veya ayarlar. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Damganın sağ kenar boşluğunu alır veya ayarlar. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Damga içeriğinin [`Rotation`](../rotation/) değerlerine göre döndürülmesini ayarlar veya alır. Not: Bu özellik, 90 derece (0, 90, 180, 270 derece) katları olan açıları ayarlamak içindir. Rastgele bir açı ayarlamak için RotateAngle özelliğini kullanın. Eğer RastgeleAçı tarafından ayarlanan açı 90'ın katı değilse, Rotate özelliği Rotation.None döner. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Damganın derece cinsinden döndürme açısını alır veya ayarlar. Bu özellik, rastgele döndürme açısı ayarlamaya olanak tanır. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Damganın üst kenar boşluğunu alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Sayfadaki damganın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Sayfadaki damganın istenen genişliği. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Soldan başlayarak yatay damga koordinatı. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Aşağıdan başlayarak dikey damga koordinatı. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Damganın yakınlaştırma faktörü. Damgayı ölçeklendirmeye olanak tanır. Lütfen ZoomX ve ZoomY çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya olanak tanıdığını unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. Eğer ZoomX ve ZoomY farklıysa, Zoom özelliği ZoomX değerini döner. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Damganın yatay yakınlaştırma faktörü. Damgayı yatay olarak ölçeklendirmeye olanak tanır. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Damganın dikey yakınlaştırma faktörü. Damgayı dikey olarak ölçeklendirmeye olanak tanır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Damga ID'sini döner. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Belirtilen sayfaya damgayı koyar. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Damga ID'sini ayarlar. |

### Ayrıca Bakınız

* sınıf [Stamp](../stamp/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)