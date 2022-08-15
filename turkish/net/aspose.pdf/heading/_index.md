---
title: Heading
second_title: Aspose.PDF for .NET API Referansı
description: Başlığı temsil eder.
type: docs
weight: 3360
url: /tr/net/aspose.pdf/heading/
---
## Heading class

Başlığı temsil eder.

```csharp
public sealed class Heading : TextFragment
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Heading](heading)(int) | Cell sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | İle temsil edilen metin için metin konumunu alır[`TextFragment`](../../aspose.pdf.text/textfragment) object. Konum yapısının YIndent'i, metin parçasının temel koordinatını temsil eder. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Hedef sayfayı alır. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Paragraf son notunu alır veya ayarlar.(yalnızca pdf oluşturma için) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Paragraf dip notunu alır veya ayarlar.(yalnızca pdf oluşturma için) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | TextFragment öğesini içeren form nesnesini alır |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Metin parçasının yatay hizalamasını alır veya ayarlar. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | hyperlink parçasını ayarlar |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Başlığın otomatik olarak numaralandırılması gerektiğini alır. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Başlığın toc listesinde olması gerektiğini alır. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Seviyeyi alır. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | TextFragment içeren sayfayı alır |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | İle temsil edilen metin için metin konumunu alır veya ayarlar[`TextFragment`](../../aspose.pdf.text/textfragment) nesne. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | TextFragment 'nin dikdörtgenini alır |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun olarak değiştirildiğinde davranışı tanımlar. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Geçerli metin segmentlerini alır[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Yön başlangıç numarasını alır. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Stili alır veya ayarlar. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Alır veya ayarlarString olan metin nesnesi[`TextFragment`](../../aspose.pdf.text/textfragment) nesne temsil eder. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Metin için metin durumunu alır veya ayarlar.[`TextFragment`](../../aspose.pdf.text/textfragment) nesne temsil eder. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Bu başlığı içeren sayfayı alır. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Bu başlıkların ilk Y'sini alır. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Kullanıcı etiketini alır veya ayarlar. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Metin parçasının dikey hizalamasını alır veya ayarlar. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Bu paragraf için sarma satırlarının sayısını alır veya ayarlar (yalnızca pdf oluşturma için) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Başlığı klonlayın. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Başlığı tüm segmentlerle klonlayın. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Alır[`TextSegment`](../../aspose.pdf.text/textsegment) (ler) belirtilen kısmı temsil eden[`TextFragment`](../../aspose.pdf.text/textfragment) metin. |

### Ayrıca bakınız

* class [TextFragment](../../aspose.pdf.text/textfragment)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
