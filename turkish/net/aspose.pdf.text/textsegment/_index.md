---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment sınıfı. Pdf metninin segmentini temsil eder
type: docs
weight: 11050
url: /tr/net/aspose.pdf.text/textsegment/
---
## TextSegment sınıfı

Pdf metninin segmentini temsil eder.

```csharp
public sealed class TextSegment
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | TextSegment nesnesi oluşturur. |
| [TextSegment](textsegment/#constructor_1)(string) | TextSegment nesnesi oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | `TextSegment` nesnesi ile temsil edilen metin için metin konumunu alır. Position yapısının YIndent'i metin segmentinin temel koordinatını temsil eder. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Metin segmentindeki karakterler hakkında bilgi veren CharInfo nesnelerinin koleksiyonunu alır. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Gösterim metni operatöründeki (Tj, TJ) mevcut segmentin son karakter indeksini alır. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Segmentin köprü bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | `TextSegment` nesnesi ile temsil edilen metin için metin konumunu alır. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | TextSegment'in dikdörtgenini alır. |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Gösterim metni operatöründeki (Tj, TJ) mevcut segmentin başlangıç karakter indeksini alır. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | `TextSegment` nesnesinin temsil ettiği String metin nesnesini alır veya ayarlar. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembolün yazı tipi ile yazılamadığı durumlarda özel davranışı tanımlar. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | `TextSegment` nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Dizeyi html olarak kodlar. |

## Açıklamalar

Kısaca, `TextSegment` nesneleri [`TextFragment`](../textfragment/) nesnesinin çocuklarıdır. Ayrıntılı olarak: Pdf belgesinin metni, iki temel nesne ile temsil edilir: [`TextFragment`](../textfragment/) ve `TextSegment`. Aralarındaki farklar çoğunlukla bağlama bağlıdır. Aşağıdaki senaryoyu düşünelim. Kullanıcı "hello world" metnini arar, onunla işlem yapmak, özelliklerini değiştirmek, bakmak vb.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Pdf metninin fiziksel temsili oldukça karmaşıktır. "hello world" metni birkaç fiziksel olarak bağımsız metin segmentinden oluşabilir. Aspose.Pdf metin modeli esasen, [`TextFragment`](../textfragment/) nesnesinin, kullanıcının sorgusunu temsil eden fiziksel `TextSegment` nesneleri kümesi üzerinde tek bir mantıksal işlem seti sağladığını belirler. Metin arama senaryosunda, [`TextFragment`](../textfragment/) mantıksal "hello world" metin temsilidir ve `TextSegment` nesne koleksiyonu "hello world" metin nesnesini oluşturan tüm fiziksel segmentleri temsil eder. Böylece, [`TextFragment`](../textfragment/) mantıksal metin temsilinde yakındır. Ve `TextSegment` fiziksel metin temsilinde yakındır. Açıkça her `TextSegment` nesnesinin kendi yazı tipi, renk, konumlandırma özellikleri olabilir. [`TextFragment`](../textfragment/) metni özellikleriyle değiştirmek için basit bir yol sağlar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada `TextSegment` nesneleri erişilebilir ve kullanıcılar `TextSegment` nesneleri ile bağımsız olarak işlem yapabilirler.

## Örnekler

Örnek, `TextSegment` nesnesinin [`TextState`](./textstate/) nesnesi ile metin rengini ve yazı tipi boyutunu nasıl değiştireceğini gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)