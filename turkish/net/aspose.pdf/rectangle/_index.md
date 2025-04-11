---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Rectangle sınıfı. Sınıf dikdörtgeni temsil eder
type: docs
weight: 9750
url: /tr/net/aspose.pdf/rectangle/
---
## Dikdörtgen sınıfı

Sınıf dikdörtgeni temsil eder.

```csharp
public sealed class Rectangle : ICloneable
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Dikdörtgenin yapıcısı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Boş dikdörtgen |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Sıfır konum ve boyuta sahip trivial dikdörtgeni başlatır. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Dikdörtgenin yüksekliği. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Dikdörtgenin boş olup olmadığını kontrol eder. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Dikdörtgenin bir nokta olup olmadığını kontrol eder; yani LLX URX'e ve LLY URY'ye eşittir. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Dikdörtgenin trivial olup olmadığını kontrol eder; yani sıfır boyut ve konuma sahiptir. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Alt-sol köşenin X koordinatı. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Alt-sol köşenin Y koordinatı. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Üst-sağ köşenin X koordinatı. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Üst-sağ köşenin Y koordinatı. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Dikdörtgenin genişliği. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Dizeyi çözmeye çalışır ve dikdörtgen bileşenlerini llx, lly, urx, ury çıkarır. |
| [Center](../../aspose.pdf/rectangle/center/)() | Dikdörtgenin merkezinin koordinatlarını döndürür. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Dikdörtgen nesnesini kopyalar. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Verilen noktanın dikdörtgenin içinde olup olmadığını belirler. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Dikdörtgenin iki nokta ile temsil edilen bir çizgiyi içerip içermediğini belirler. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Verilen noktanın dikdörtgenin içinde olup olmadığını belirler. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Dikdörtgenlerin eşit olup olmadığını kontrol eder; yani aynı konum ve boyutlara sahip olup olmadıklarını. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Dikdörtgenleri kesiştirir. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Bu dikdörtgenin diğer dikdörtgenle kesişip kesişmediğini belirler. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Dikdörtgenleri birleştirir. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Dikdörtgeni belirtilen delta değerleriyle kaydırır. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Dikdörtgenlerin yakın eşit olup olmadığını kontrol eder; yani yakın aynı (delta kadar) konum ve boyutlara sahip olup olmadıklarını. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Dikdörtgeni belirtilen açıyla döndürür. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Dikdörtgeni belirtilen açıyla döndürür. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Dikdörtgeni nokta dizisine ("QuadPoints") dönüştürür. |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Dikdörtgeni System.Drawing.Rectangle örneğine dönüştürür. Ondalık konumlar ve boyutlar kesilir. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Dikdörtgenin dize temsilini alır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)