---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragment sınıfı. Pdf metninin parçasını temsil eder
type: docs
weight: 10940
url: /tr/net/aspose.pdf.text/textfragment/
---
## TextFragment sınıfı

Pdf metninin parçasını temsil eder.

```csharp
public class TextFragment : BaseParagraph
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | `TextFragment` nesnesinin yeni bir örneğini başlatır. |
| [TextFragment](textfragment/#constructor_2)(string) | İçinde tek bir [`TextSegment`](../textsegment/) nesnesi bulunan `TextFragment` nesnesi oluşturur. Segment içindeki metin dizesini belirtir. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Önceden tanımlanmış [`TabStops`](../tabstops/) konumları ile `TextFragment` nesnesinin yeni bir örneğini başlatır. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | İçinde tek bir [`TextSegment`](../textsegment/) nesnesi bulunan ve önceden tanımlanmış [`TabStops`](../tabstops/) konumları ile `TextFragment` nesnesi oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | `TextFragment` nesnesi ile temsil edilen metin için metin konumunu alır. Position yapısının YIndent'i metin parçasının temel koordinatını temsil eder. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Paragraf son notunu alır veya ayarlar. (sadece pdf oluşturma için) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Paragraf dipnotunu alır veya ayarlar. (sadece pdf oluşturma için) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment'i içeren form nesnesini alır |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Metin parçasının yatay hizalamasını alır veya ayarlar. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Parça köprü bağlantısını ayarlar |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment'i içeren sayfayı alır |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | `TextFragment` nesnesi ile temsil edilen metin için metin konumunu alır veya ayarlar. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment'in dikdörtgenini alır |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Mevcut `TextFragment` için metin segmentlerini alır. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | `TextFragment` nesnesinin temsil ettiği String metin nesnesini alır veya ayarlar. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembolün yazı tipi ile yazılamadığı durumlarda özel davranışı tanımlar. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | `TextFragment` nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Metin parçasının dikey hizalamasını alır veya ayarlar. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Bu paragraf için sarma satır sayısını alır veya ayarlar (sadece pdf oluşturma için) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Parçayı klonlar. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Tüm segmentlerle parçayı klonlar. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | `TextFragment` metninin belirtilen kısmını temsil eden [`TextSegment`](../textsegment/) (leri) alır. |

## Açıklamalar

Kısaca, `TextFragment` nesnesi bir dizi [`TextSegment`](../textsegment/) nesnesi içerir. Ayrıntılı olarak: Pdf belgesinin metni, iki temel nesne ile temsil edilir: `TextFragment` ve [`TextSegment`](../textsegment/) Aralarındaki farklar çoğunlukla bağlama bağlıdır. Aşağıdaki senaryoyu düşünelim. Kullanıcı "hello world" metnini arar, onunla işlem yapmak, özelliklerini değiştirmek, bakmak vb.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Pdf metninin fiziksel temsili oldukça karmaşıktır. "hello world" metni, birkaç fiziksel olarak bağımsız metin segmentinden oluşabilir. Aspose.Pdf metin modeli esasen `TextFragment` nesnesinin, kullanıcının sorgusunu temsil eden fiziksel [`TextSegment`](../textsegment/) nesneleri kümesi üzerinde tek bir mantıksal işlem seti sağladığını belirler. Metin arama senaryosunda, `TextFragment` mantıksal "hello world" metin temsilidir ve [`TextSegment`](../textsegment/) nesne koleksiyonu "hello world" metin nesnesini oluşturan tüm fiziksel segmentleri temsil eder. Bu nedenle, `TextFragment` mantıksal metin temsilinde yakındır. Ve [`TextSegment`](../textsegment/) fiziksel metin temsilinde yakındır. Açıkça, her [`TextSegment`](../textsegment/) nesnesinin kendi yazı tipi, renk, konumlandırma özellikleri olabilir. `TextFragment`, metni ve özelliklerini değiştirmek için basit bir yol sağlar: yazı tipini ayarlamak, yazı tipi boyutunu ayarlamak, yazı tipi rengini ayarlamak vb. Bu arada, [`TextSegment`](../textsegment/) nesneleri erişilebilir ve kullanıcılar [`TextSegment`](../textsegment/) nesneleri ile bağımsız olarak işlem yapabilirler. `TextFragment` özelliklerini değiştirmenin, iç [`Segments`](./segments/) koleksiyonunu değiştirebileceğini unutmayın çünkü TextFragment bir toplama nesnesidir ve iç segmentleri yeniden düzenleyebilir veya bunları tek bir segmentte birleştirebilir. Eğer gereksiniminiz [`Segments`](./segments/) koleksiyonunu değiştirmeden bırakmaksa, lütfen iç segmentleri bireysel olarak değiştirin.

## Örnekler

Örnek, ilk PDF belgesi sayfasında metni bulmayı ve metni ve yazı tipini değiştirmeyi gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* sınıf [BaseParagraph](../../aspose.pdf/baseparagraph/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)