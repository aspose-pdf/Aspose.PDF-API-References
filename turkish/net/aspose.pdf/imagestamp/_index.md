---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp sınıfı. Grafik damga temsil eder
type: docs
weight: 5930
url: /tr/net/aspose.pdf/imagestamp/
---
## ImageStamp sınıfı

Grafik damga temsil eder.

```csharp
public sealed class ImageStamp : Stamp
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | `ImageStamp` sınıfının yeni bir örneğini başlatır. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Belirtilen dosyadaki resim ile resim damgası oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Resim damgası için Alternatif Metni alır veya ayarlar. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | İçeriğin arka plan olarak damgalandığını belirten bir bool değeri ayarlar veya alır. Değer true ise, damga içeriği en altta yer alır. Varsayılan olarak, değer false'tur, damga içeriği en üstte yer alır. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Damganın alt kenar boşluğunu alır veya ayarlar. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Resim yüksekliğini alır veya ayarlar. Bu resmi ayarlamak, resmi dikey olarak ölçeklendirmeye olanak tanır. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Sayfadaki damganın yatay hizalamasını alır veya ayarlar. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Damgalama için kullanılan resim akışını alır. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Damganın sol kenar boşluğunu alır veya ayarlar. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Damga opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan olarak değer 1.0'dır. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Damga dış hat opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan olarak değer 1.0'dır. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Damga dış hat genişliğinin bir değerini alır veya ayarlar. Varsayılan olarak değer 1.0'dır. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Resim damgasının kalitesini yüzde olarak alır veya ayarlar. Geçerli değerler 0..100%'dir. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Damganın sağ kenar boşluğunu alır veya ayarlar. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Damga içeriğinin [`Rotation`](../rotation/) değerlerine göre döndürülmesini ayarlar veya alır. Not. Bu özellik, 90 derece (0, 90, 180, 270 derece) katları olan açıları ayarlamak içindir. Keyfi bir açı ayarlamak için RotateAngle özelliğini kullanın. Eğer KeyfiAçı ile ayarlanan açı 90'ın katı değilse, Rotate özelliği Rotation.None döner. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Damganın derece cinsinden döndürme açısını alır veya ayarlar. Bu özellik, keyfi bir döndürme açısı ayarlamaya olanak tanır. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Damganın üst kenar boşluğunu alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Sayfadaki damganın dikey hizalamasını alır veya ayarlar. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Resim genişliğini alır veya ayarlar. Bu özelliği ayarlamak, resmi yatay olarak ölçeklendirmeye olanak tanır. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Soldan başlayarak yatay damga koordinatını alır ve ayarlar. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Aşağıdan başlayarak dikey damga koordinatını alır ve ayarlar. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Damganın zoom faktörü. Damgayı ölçeklendirmeye olanak tanır. Lütfen ZoomX ve ZoomY çiftinin her eksen için ayrı zoom faktörü ayarlamaya olanak tanıdığını unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. Eğer ZoomX ve ZoomY farklıysa, Zoom özelliği ZoomX değerini döner. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Damganın yatay zoom faktörü. Damgayı yatay olarak ölçeklendirmeye olanak tanır. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Damganın dikey zoom faktörü. Damgayı dikey olarak ölçeklendirmeye olanak tanır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Damga ID'sini döner. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Sayfaya grafik damga ekler. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Damga Id'sini ayarlar. |

### Ayrıca Bakınız

* sınıf [Stamp](../stamp/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)