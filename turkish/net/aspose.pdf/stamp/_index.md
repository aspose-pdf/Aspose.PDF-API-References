---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Stamp sınıfı. Çeşitli türde damgalar için soyut bir sınıf.
type: docs
weight: 10130
url: /tr/net/aspose.pdf/stamp/
---
## Damga Sınıfı

Çeşitli türde damgalar için soyut bir sınıf.

```csharp
public abstract class Stamp
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArkaPlan](../../aspose.pdf/stamp/background/) { get; set; } | İçeriğin arka plan olarak damgalandığını belirten bir bool değeri ayarlar veya alır. Değer true ise, damga içeriği en altta yer alır. Varsayılan olarak, değer false'tur, damga içeriği en üstte yer alır. |
| [AltMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Damganın alt kenar boşluğunu alır veya ayarlar. |
| sanal [Yükseklik](../../aspose.pdf/stamp/height/) { get; set; } | Sayfadaki damganın istenen yüksekliği. |
| [YatayHizalama](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Sayfadaki damganın yatay hizalamasını alır veya ayarlar. |
| [SolMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Damganın sol kenar boşluğunu alır veya ayarlar. |
| [Opaklık](../../aspose.pdf/stamp/opacity/) { get; set; } | Damga opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [ÇerçeveOpaklığı](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Damga çerçeve opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [ÇerçeveGenişliği](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Damga çerçeve genişliğinin bir değerini alır veya ayarlar. Varsayılan değer 1.0'dır. |
| [SağMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Damganın sağ kenar boşluğunu alır veya ayarlar. |
| [Döndür](../../aspose.pdf/stamp/rotate/) { get; set; } | Damga içeriğinin döndürülmesini [`Dönüş`](../rotation/) değerlerine göre ayarlar veya alır. Not. Bu özellik, 90 derece (0, 90, 180, 270 derece) katları olan açıları ayarlamak içindir. Rastgele bir açı ayarlamak için RotateAngle özelliğini kullanın. Eğer RastgeleAçı ile ayarlanan açı 90'ın katı değilse, Rotate özelliği Rotation.None döner. |
| [DöndürmeAçısı](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Damganın derece cinsinden döndürme açısını alır veya ayarlar. Bu özellik, rastgele döndürme açısı ayarlamaya olanak tanır. |
| [ÜstMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Damganın üst kenar boşluğunu alır veya ayarlar. |
| [DikeyHizalama](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Sayfadaki damganın dikey hizalamasını alır veya ayarlar. |
| sanal [Genişlik](../../aspose.pdf/stamp/width/) { get; set; } | Sayfadaki damganın istenen genişliği. |
| sanal [Xİndeks](../../aspose.pdf/stamp/xindent/) { get; set; } | Soldan başlayarak yatay damga koordinatı. |
| sanal [Yİndeks](../../aspose.pdf/stamp/yindent/) { get; set; } | Aşağıdan başlayarak dikey damga koordinatı. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Damganın yakınlaştırma faktörü. Damgayı ölçeklendirmeye olanak tanır. Lütfen ZoomX ve ZoomY çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya olanak tanıdığını unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. Eğer ZoomX ve ZoomY farklıysa, Zoom özelliği ZoomX değerini döner. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Damganın yatay yakınlaştırma faktörü. Damgayı yatay olarak ölçeklendirmeye olanak tanır. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Damganın dikey yakınlaştırma faktörü. Damgayı dikey olarak ölçeklendirmeye olanak tanır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Damga kimliğini döner. |
| soyut [Put](../../aspose.pdf/stamp/put/)(Sayfa) | Sayfaya damga ekler. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Damga kimliğini ayarlar. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)