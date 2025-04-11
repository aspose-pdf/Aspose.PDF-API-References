---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextState sınıfı. Bir metin durumunu temsil eder
type: docs
weight: 11070
url: /tr/net/aspose.pdf.text/textstate/
---
## TextState sınıfı

Bir metin durumunu temsil eder

```csharp
public class TextState
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextState](textstate/#constructor)() | Metin durumu nesnesi oluşturur. |
| [TextState](textstate/#constructor_2)(Color) | Ön plan rengi belirtimi ile metin durumu nesnesi oluşturur. |
| [TextState](textstate/#constructor_1)(double) | Yazı tipi boyutu belirtimi ile metin durumu nesnesi oluşturur. |
| [TextState](textstate/#constructor_4)(string) | Yazı tipi ailesi belirtimi ile metin durumu nesnesi oluşturur. |
| [TextState](textstate/#constructor_3)(Color, double) | Ön plan rengi ve yazı tipi boyutu belirtimi ile metin durumu nesnesi oluşturur. |
| [TextState](textstate/#constructor_6)(string, double) | Yazı tipi ailesi ve yazı tipi boyutu belirtimi ile metin durumu nesnesi oluşturur. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Yazı tipi ailesi ve yazı tipi stili belirtimi ile metin durumu nesnesi oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Metnin arka plan rengini ayarlar. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Metnin karakter aralığını alır veya ayarlar. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Metin CoordinateOrigin'ini alır veya ayarlar. Eğer CoordinateOrigin Descender ise, metin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. Eğer CoordinateOrigin BaseLine ise, metin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Eğer yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek render edilebilir. Bu durumda, daha iyi metin render'ı için CoordinateOrigin BaseLine seçilebilir. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Metnin yazı tipini alır veya ayarlar. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Metnin yazı tipi boyutunu alır veya ayarlar. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Metnin yazı tipi stilini ayarlar. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Metnin ön plan rengini alır veya ayarlar. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Metin için yatay hizalamayı alır veya ayarlar. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Metnin yatay ölçeklemesini alır veya ayarlar. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Metnin görünmezliğini alır veya ayarlar. Bu, esasen [`RenderingMode`](./renderingmode/) durumunu yansıtır, bazı özel durumlar (kesme gibi) hariç. |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Metnin satır aralığını alır veya ayarlar. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Metnin render modunu alır veya ayarlar. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Metin için üstü çizili durumu alır veya ayarlar, [`TextSegment`](../textsegment/) nesnesi ile temsil edilir. |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Metnin ön plan rengini alır veya ayarlar. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Metnin alt simgesini alır veya ayarlar. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Metnin üst simgesini alır veya ayarlar. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Metin için altı çizili durumu alır veya ayarlar, [`TextFragment`](../textfragment/) nesnesi ile temsil edilir. |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Metnin kelime aralığını alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Başka bir textState'den ayarları uygular. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Karakter yüksekliğini ölçer. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Dizeyi ölçer. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Varsayılan yazı tipinin boşluk karakteri genişliklerinde sekme için varsayılan değerdir. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Sekmeyi belirtmek için metne bu etiketi yerleştirebilirsiniz. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)