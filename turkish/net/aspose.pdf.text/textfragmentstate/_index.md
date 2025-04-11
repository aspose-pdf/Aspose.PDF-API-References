---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentState sınıfı. Bir metin parçasının metin durumunu temsil eder
type: docs
weight: 10970
url: /tr/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState sınıfı

Bir metin parçasının metin durumunu temsil eder.

```csharp
public sealed class TextFragmentState : TextState
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Belirtilen [`TextFragment`](../textfragment/) nesnesi ile `TextFragmentState` nesnesinin yeni bir örneğini başlatır. Bu `TextFragmentState` başlatması desteklenmemektedir. TextFragmentState yalnızca [`TextState`](../textfragment/textstate/) özelliği ile kullanılabilir. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin arka plan rengini ayarlar |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin karakter aralığını alır veya ayarlar. |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Metin Koordinat Orijini'ni alır veya ayarlar. Koordinat Orijini Descender ise, metin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. Koordinat Orijini BaseLine ise, metin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek bir şekilde işlenebilir. Bu durumda, daha iyi metin işleme için Koordinat Orijini BaseLine seçilebilir. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Metin dikdörtgen kenarının çizilip çizilmeyeceğini alır veya ayarlar. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin yazı tipini alır veya ayarlar |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin yazı tipi boyutunu alır veya ayarlar |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin yazı tipi stilini ayarlar |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin ön plan rengini alır veya ayarlar |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Biçimlendirme seçeneklerini alır veya ayarlar. Seçeneklerin ayarlanması yalnızca üretici senaryolarında etkili olacaktır. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Metin için yatay hizalamayı alır veya ayarlar. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin yatay ölçeklemesini alır veya ayarlar. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Metnin görünmezliğini alır veya ayarlar. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Metnin satır aralığını alır veya ayarlar. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Metnin işleme modunu alır veya ayarlar. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Derece cinsinden döndürme açısını alır veya ayarlar. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metin için üstü çizili durumu alır veya ayarlar |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | [`TextFragment`](../textfragment/) işleme (metin çizgisi, dikdörtgen kenarı) için renk çizme işlemlerini alır veya ayarlar |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin alt simgesini alır veya ayarlar. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metnin üst simgesini alır veya ayarlar. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Metin için sekme duraklarını alır. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | [`TextFragment`](../textfragment/) nesnesi tarafından temsil edilen metin için altı çizili durumu alır veya ayarlar |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Metnin kelime aralığını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Başka bir textState'den ayarları uygular. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Girdi dizesinin tanımlanan dikdörtgenin içine yerleştirilip yerleştirilemeyeceğini kontrol eder. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Karakter yüksekliğini ölçer. (2 yöntem) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Dizeyi ölçer. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Varsayılan yazı tipinin boşluk karakterinin genişliklerinde sekme için varsayılan değeri. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Sekmeyi belirtmek için metne bu etiketi yerleştirebilirsiniz. |

## Notlar

Aşağıdaki metin özelliklerini değiştirmek için bir yol sağlar: yazı tipi ([`Font`](./font/) özelliği) yazı tipi boyutu ([`FontSize`](./fontsize/) özelliği) yazı tipi stili ([`FontStyle`](./fontstyle/) özelliği) ön plan rengi ([`ForegroundColor`](./foregroundcolor/) özelliği) arka plan rengi ([`BackgroundColor`](./backgroundcolor/) özelliği) `TextFragmentState` özelliklerini değiştirmenin, içindeki [`Segments`](../textfragment/segments/) koleksiyonunu değiştirebileceğini unutmayın çünkü TextFragment bir toplama nesnesidir ve iç segmentleri yeniden düzenleyebilir veya bunları tek bir segmentte birleştirebilir. Eğer amacınız [`Segments`](../textfragment/segments/) koleksiyonunu değiştirmeden bırakmaksa, lütfen iç segmentleri bireysel olarak değiştirin.

## Örnekler

Örnek, [`TextState`](../textstate/) nesnesi ile metin rengini ve yazı tipi boyutunu nasıl değiştireceğini gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)