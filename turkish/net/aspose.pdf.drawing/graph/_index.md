---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph sınıfı. Grafik grafik üretici paragrafını temsil eder.
type: docs
weight: 3940
url: /tr/net/aspose.pdf.drawing/graph/
---
## Grafiği sınıfı

Grafik - grafik üretici paragrafını temsil eder.

```csharp
public sealed class Graph : BaseParagraph
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | `Graph` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Kenarlığı alır veya ayarlar. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Renk, çizgi kalınlığı vb. gibi grafik bilgilerini belirten bir [`GraphInfo`](./graphinfo/) nesnesini alır veya ayarlar. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Grafik yüksekliğini belirten bir float değerini alır veya ayarlar. Birim puandır. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Paragrafın yatay hizalamasını alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü (pdf üreticisi için) alır veya ayarlar. |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Paragrafı işleme aldıktan sonra mevcut konumu değiştirmeyi alır veya ayarlar. (varsayılan doğru) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan yanlış. (pdf üretimi için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan yanlış. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada üretilmesini zorlayan bir bool değerini alır veya ayarlar. Varsayılan yanlış. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan yanlış. (pdf üretimi için) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Tablo sol koordinatını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış marjı alır veya ayarlar (pdf üretimi için) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Grafikteki tüm şekilleri belirten bir [`Shapes`](./shapes/) koleksiyonunu alır veya ayarlar. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Grafiğin başlığını belirten bir string değerini alır veya ayarlar. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Tablo üst koordinatını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Grafik genişliğini belirten bir float değerini alır veya ayarlar. Birim puandır. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Grafiği kopyalar. |

### Ayrıca Bakınız

* sınıf [BaseParagraph](../../aspose.pdf/baseparagraph/)
* ad alanı [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* derleme [Aspose.PDF](../../)