---
title: TextFragmentState
second_title: Aspose.PDF for .NET API Referansı
description: Bir metin parçasının metin durumunu temsil eder.
type: docs
weight: 7130
url: /tr/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Bir metin parçasının metin durumunu temsil eder.

```csharp
public sealed class TextFragmentState : TextState
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Yeni örneğini başlatır[`TextFragmentState`](../textfragmentstate) belirtilen nesne[`TextFragment`](../textfragment) nesne. Bu[`TextFragmentState`](../textfragmentstate) başlatma desteklenmiyor. TextFragmentState yalnızca[`TextState`](../textfragment/textstate) özellik. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | ile temsil edilen metnin arka plan rengini ayarlar.[`TextFragment`](../textfragment) nesne |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | ile temsil edilen metnin karakter aralığını alır veya ayarlar.[`TextFragment`](../textfragment) nesne. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Metin dikdörtgen kenarlıklı bayrak çizilirse alır veya ayarlar. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | İle temsil edilen metnin yazı tipini alır veya ayarlar.[`TextFragment`](../textfragment) nesne |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | İle temsil edilen metnin yazı tipi boyutunu alır veya ayarlar.[`TextFragment`](../textfragment) nesne |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | ile temsil edilen metnin yazı tipi stilini ayarlar.[`TextFragment`](../textfragment) nesne |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Metin tarafından temsil edilen metnin ön plan rengini alır veya ayarlar.[`TextFragment`](../textfragment) nesne |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Biçimlendirme seçeneklerini alır veya ayarlar. Seçeneklerin ayarlanması yalnızca oluşturucu senaryolarında etkili olacaktır. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Metin için yatay hizalamayı alır veya ayarlar. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | tarafından temsil edilen metnin yatay ölçeklemesini alır veya ayarlar.[`TextFragment`](../textfragment) nesne. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Metnin görünmezliğini alır veya ayarlar. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Metnin satır aralığını alır veya ayarlar. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Metnin oluşturma modunu alır veya ayarlar. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Dönme açısını derece cinsinden alır veya ayarlar. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | tarafından temsil edilen metin için üstü çizili olarak ayarlar.[`TextFragment`](../textfragment) nesne |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Şunun renk vuruş işlemlerini alır veya ayarlar:[`TextFragment`](../textfragment) oluşturma (kontur metni, dikdörtgen kenarlık) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | İle temsil edilen metnin alt simgesini alır veya ayarlar.[`TextFragment`](../textfragment) nesne. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | İle temsil edilen metnin üst simgesini alır veya ayarlar.[`TextFragment`](../textfragment) nesne. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Metin için sekme duraklarını alır. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Metin için alt çizgiyi alır veya ayarlar.[`TextFragment`](../textfragment) nesne |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Metnin sözcük aralığını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Başka bir textState'den gelen ayarları uygular. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Dizeyi ölçer. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Varsayılan yazı tipinin boşluk karakterinin genişliklerinde tablolaştırmanın varsayılan değeri. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Bu etiketi, tablolamayı bildirmek için metne yerleştirebilirsiniz. |

### Notlar

Metnin aşağıdaki özelliklerini değiştirmenin bir yolunu sağlar: yazı tipi ([`Font`](./font) özellik) yazı tipi boyutu ([`FontSize`](./fontsize) özellik) yazı tipi stili ([`FontStyle`](./fontstyle) özellik) ön plan rengi ([`ForegroundColor`](./foregroundcolor) özellik) arka plan rengi ([`BackgroundColor`](./backgroundcolor) property) Değişen[`TextFragmentState`](../textfragmentstate) özellikler iç değişebilir[`Segments`](../textfragment/segments) toplama, çünkü TextFragment bir toplu nesne ve dahili segmentleri yeniden düzenleyebilir veya bunları tek segmentte birleştirebilir. Gereksiniminiz[`Segments`](../textfragment/segments) koleksiyon değişmedi, lütfen iç segmentleri ayrı ayrı değiştirin.

### Örnekler

Örnek, metin renginin ve yazı tipi boyutunun nasıl değiştirileceğini gösterir.[`TextState`](../textstate) nesne.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun ön plan rengini değiştir
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// İlk metin oluşumunun yazı tipi boyutunu değiştir
absorber.TextFragments[1].TextState.FontSize = 15;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
