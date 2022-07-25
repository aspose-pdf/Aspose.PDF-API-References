---
title: TextSegment
second_title: Aspose.PDF for .NET API Referansı
description: Pdf metninin segmentini temsil eder.
type: docs
weight: 7210
url: /tr/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Pdf metninin segmentini temsil eder.

```csharp
public sealed class TextSegment
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextSegment](textsegment#constructor)() | TextSegment nesnesi oluşturur. |
| [TextSegment](textsegment#constructor_1)(string) | TextSegment nesnesi oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | İle temsil edilen metin için metin konumunu alır[`TextSegment`](../textsegment) object. Konum yapısının YIndent'i, metin segmentinin temel koordinatını temsil eder. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Metin kesimindeki karakterlerle ilgili bilgileri temsil eden CharInfo nesnelerinin koleksiyonunu alır. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Metin gösterme operatörü (Tj, TJ) segmentindeki geçerli segmentin bitiş karakter dizinini alır. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Segment köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | İle temsil edilen metin için metin konumunu alır[`TextSegment`](../textsegment) nesne. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | TextSegment 'nin dikdörtgenini alır |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Metin gösterme operatörü (Tj, TJ) segmentindeki geçerli segmentin başlangıç karakter dizinini alır. |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Alır veya ayarlarString olan metin nesnesi[`TextSegment`](../textsegment) nesne temsil eder. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembol font ile yazılamadığında özel davranışı tanımlar. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Metin için metin durumunu alır veya ayarlar.[`TextSegment`](../textsegment) nesne temsil eder. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Dizeyi html. olarak kodlar |

### Notlar

Birkaç kelimeyle,[`TextSegment`](../textsegment) nesneler çocuklarıdır[`TextFragment`](../textfragment) object. Ayrıntılarda: İçindeki pdf belgesinin metniPdf iki temel nesne ile temsil edilir:[`TextFragment`](../textfragment) ve[`TextSegment`](../textsegment) Aralarındaki farklar çoğunlukla bağlama bağlıdır. Aşağıdaki senaryoyu ele alalım. Kullanıcı onunla çalışmak, özelliklerini değiştirmek, bakmak vb. için "merhaba dünya" metnini arar. Fiziksel olarak pdf metninin gösterimi çok karmaşıktır. "Merhaba dünya" metni, fiziksel olarak bağımsız birkaç metin bölümünden oluşabilir. Aspose.Pdf metin modeli temel olarak şunu belirler:[`TextFragment`](../textfragment) object , fiziksel olarak ayarlanmış tek bir mantık işlemi sağlar[`TextSegment`](../textsegment) kullanıcının sorgusunu temsil eden nesneler kümesi. Metin arama senaryosunda,[`TextFragment`](../textfragment) mantıksal "merhaba dünya" metin gösterimidir, ve[`TextSegment`](../textsegment)nesne koleksiyonu, "merhaba dünya" metin nesnesini oluşturan tüm fiziksel bölümleri temsil eder. Yani,[`TextFragment`](../textfragment) mantıksal metin gösterimine yakındır. Ve[`TextSegment`](../textsegment) fiziksel metin gösterimine yakındır. Açıkça her biri[`TextSegment`](../textsegment) nesnenin kendi yazı tipi, renklendirme, konumlandırma özellikleri olabilir. [`TextFragment`](../textfragment) özellikleriyle metni değiştirmek için basit bir yol sağlar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada[`TextSegment`](../textsegment) nesnelere erişilebilir ve kullanıcılar ile çalışabilir[`TextSegment`](../textsegment) nesneleri bağımsız olarak.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Örnekler

Örnek, metin renginin ve yazı tipi boyutunun nasıl değiştirileceğini gösterir.[`TextState`](./textstate) Nesnesi[`TextSegment`](../textsegment) nesne.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun ilk metin bölümünün ön plan rengini değiştirin
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// İlk metin oluşumunun ilk metin bölümünün yazı tipi boyutunu değiştir
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
