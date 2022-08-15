---
title: TextFragment
second_title: Aspose.PDF for .NET API Referansı
description: Pdf metninin bir parçasını temsil eder.
type: docs
weight: 7100
url: /tr/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Pdf metninin bir parçasını temsil eder.

```csharp
public class TextFragment : BaseParagraph
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Yeni örneğini başlatır[`TextFragment`](../textfragment) nesne. |
| [TextFragment](textfragment#constructor_2)(string) | Oluşturur[`TextFragment`](../textfragment) tek ile nesne[`TextSegment`](../textsegment) içindeki nesne. Segment içindeki metin dizesini belirtir. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Yeni örneğini başlatır[`TextFragment`](../textfragment) önceden tanımlanmış nesne[`TabStops`](../tabstops) pozisyonlar. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Oluşturur[`TextFragment`](../textfragment) tek ile nesne[`TextSegment`](../textsegment) nesne içinde ve önceden tanımlanmış[`TabStops`](../tabstops) pozisyonlar. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | İle temsil edilen metin için metin konumunu alır[`TextFragment`](../textfragment) object. Konum yapısının YIndent'i, metin parçasının temel koordinatını temsil eder. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Paragraf son notunu alır veya ayarlar.(yalnızca pdf oluşturma için) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Paragraf dip notunu alır veya ayarlar.(yalnızca pdf oluşturma için) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | TextFragment öğesini içeren form nesnesini alır |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Metin parçasının yatay hizalamasını alır veya ayarlar. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | hyperlink parçasını ayarlar |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | TextFragment içeren sayfayı alır |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | İle temsil edilen metin için metin konumunu alır veya ayarlar[`TextFragment`](../textfragment) nesne. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | TextFragment 'nin dikdörtgenini alır |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun olarak değiştirildiğinde davranışı tanımlar. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Geçerli metin segmentlerini alır[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Alır veya ayarlarString olan metin nesnesi[`TextFragment`](../textfragment) nesne temsil eder. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Metin için metin durumunu alır veya ayarlar.[`TextFragment`](../textfragment) nesne temsil eder. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Metin parçasının dikey hizalamasını alır veya ayarlar. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Bu paragraf için sarma satırlarının sayısını alır veya ayarlar (yalnızca pdf oluşturma için) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Parçayı klonlayın. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Parçayı tüm segmentlerle klonlayın. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Alır[`TextSegment`](../textsegment) (ler) belirtilen kısmı temsil eden[`TextFragment`](../textfragment) metin. |

### Notlar

Birkaç kelimeyle,[`TextFragment`](../textfragment) nesne listesini içerir[`TextSegment`](../textsegment) nesneler. Ayrıntılarda: İçindeki pdf belgesinin metniPdf iki temel nesne ile temsil edilir:[`TextFragment`](../textfragment) ve[`TextSegment`](../textsegment) Aralarındaki farklar çoğunlukla bağlama bağlıdır. Aşağıdaki senaryoyu ele alalım. Kullanıcı onunla çalışmak, özelliklerini değiştirmek, bakmak vb. için "merhaba dünya" metnini arar. Fiziksel olarak pdf metninin gösterimi çok karmaşıktır. "Merhaba dünya" metni, fiziksel olarak bağımsız birkaç metin bölümünden oluşabilir. Aspose.Pdf metin modeli temel olarak şunu belirler:[`TextFragment`](../textfragment) object , fiziksel olarak ayarlanmış tek bir mantık işlemi sağlar[`TextSegment`](../textsegment) kullanıcının sorgusunu temsil eden nesneler kümesi. Metin arama senaryosunda,[`TextFragment`](../textfragment) mantıksal "merhaba dünya" metin gösterimidir, ve[`TextSegment`](../textsegment)nesne koleksiyonu, "merhaba dünya" metin nesnesini oluşturan tüm fiziksel bölümleri temsil eder. Yani,[`TextFragment`](../textfragment) mantıksal metin gösterimine yakındır. Ve[`TextSegment`](../textsegment) fiziksel metin gösterimine yakındır. Açıkça her biri[`TextSegment`](../textsegment) nesnenin kendi yazı tipi, renklendirme, konumlandırma özellikleri olabilir. [`TextFragment`](../textfragment) özellikleriyle metni değiştirmek için basit bir yol sağlar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada[`TextSegment`](../textsegment) nesnelere erişilebilir ve kullanıcılar ile çalışabilir[`TextSegment`](../textsegment) nesneleri bağımsız olarak. TextFragment özelliklerini değiştirmenin iç öğeleri değiştirebileceğini unutmayın.[`Segments`](./segments) toplama, çünkü TextFragment bir toplu nesne ve dahili segmentleri yeniden düzenleyebilir veya bunları tek segmentte birleştirebilir. Gereksiniminiz[`Segments`](./segments)koleksiyon değişmedi, lütfen iç segmentleri ayrı ayrı değiştirin.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Örnekler

Örnek, ilk PDF belgesi sayfasındaki metnin nasıl bulunacağını ve metnin ve yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Belge metni yazı tipini değiştirmek için kullanılacak yazı tipini bulun
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun metnini ve yazı tipini değiştirin
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
