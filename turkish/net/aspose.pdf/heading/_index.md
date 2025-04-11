---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Heading sınıfı. Başlığı temsil eder
type: docs
weight: 5470
url: /tr/net/aspose.pdf/heading/
---
## Başlık sınıfı

Başlığı temsil eder.

```csharp
public sealed class Heading : TextFragment
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Heading](heading/)(int) | Cell sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) nesnesi ile temsil edilen metin için metin konumunu alır. Position yapısının YIndent'i metin parçasının temel koordinatını temsil eder. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Hedef sayfayı alır. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Paragraf son notunu alır veya ayarlar. (sadece pdf oluşturma için) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Paragraf dipnotunu alır veya ayarlar. (sadece pdf oluşturma için) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment'i içeren form nesnesini alır |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Metin parçasının yatay hizalamasını alır veya ayarlar. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Parça köprüsünü ayarlar |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Başlığın otomatik olarak numaralandırılması gerektiğini alır. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Başlığın toc listesinde olup olmadığını alır. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Seviyeyi alır. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış marjı alır veya ayarlar (pdf oluşturma için) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment'i içeren sayfayı alır |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) nesnesi ile temsil edilen metin için metin konumunu alır veya ayarlar. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment'in dikdörtgenini alır |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Mevcut [`TextFragment`](../../aspose.pdf.text/textfragment/) için metin parçalarını alır. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Başlık başlangıç numarasını alır. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Stili alır veya ayarlar. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) nesnesinin temsil ettiği String metin nesnesini alır veya ayarlar. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembolün yazı tipi ile yazılamadığı durumlarda özel davranışı tanımlar. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Bu başlığı içeren sayfayı alır. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Bu başlıkların üst Y'sini alır. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Kullanıcı etiketini alır veya ayarlar. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Metin parçasının dikey hizalamasını alır veya ayarlar. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Bu paragraf için sarma satır sayısını alır veya ayarlar (sadece pdf oluşturma için) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip bir grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Başlığı kopyalar. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Tüm parçalarla birlikte başlığı kopyalar. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | [`TextFragment`](../../aspose.pdf.text/textfragment/) metninin belirtilen kısmını temsil eden [`TextSegment`](../../aspose.pdf.text/textsegment/) (leri) alır. |

### Ayrıca Bakınız

* sınıf [TextFragment](../../aspose.pdf.text/textfragment/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)