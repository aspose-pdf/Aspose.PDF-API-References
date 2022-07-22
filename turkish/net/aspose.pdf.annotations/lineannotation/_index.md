---
title: LineAnnotation
second_title: Aspose.PDF for .NET API Referansı
description: Satır açıklamasını temsil eden sınıf.
type: docs
weight: 600
url: /tr/net/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class

Satır açıklamasını temsil eden sınıf.

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LineAnnotation](lineannotation#constructor)(Document, Point, Point) | Generator ile kullanmak için yapıcı. |
| [LineAnnotation](lineannotation#constructor_1)(Page, Rectangle, Point, Point) | Belirtilen sayfada yeni Satır açıklaması oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Açıklama eylemlerinin listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Geçerli ek açıklama görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype) { get; } | Açıklama türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Açıklama kenarlığı özelliklerini alır veya ayarlar.[`Border`](../annotation/border) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset) { get; set; } | Altyazı metninin normal konumundan sapmasını alır veya ayarlar. |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition) { get; set; } | Açıklama başlığı konumunu alır veya ayarlar. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Açıklama özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Açıklama rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ek açıklama metnini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Açıklamanın oluşturulduğu tarih ve saati alır. |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending) { get; set; } | Satır bitiş noktasını alır veya ayarlar. |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle) { get; set; } | Çizginin bitiş noktası için bitiş stilini alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Ek açıklamanın bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Açıklamanın tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Açıklamanın yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Bu ek açıklamanın "yanıt olarak" olduğu ek açıklama referansı. Her iki ek açıklama da belgenin aynı sayfasında olmalıdır. |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent) { get; set; } | Satır açıklamasının amacını alır veya ayarlar. |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor) { get; set; } | Açıklamanın iç rengini alır veya ayarlar. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline) { get; set; } | Öncü satır uzunluğunu alır veya ayarlar. |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension) { get; set; } | Öncü çizgi uzantısının uzunluğunu alır veya ayarlar. |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset) { get; set; } | Öncü çizgi ofsetini alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure) { get; set; } | Bu ek açıklama için belirtilen birimleri ölçün. |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Açıklamanın yakın zamanda değiştirildiği tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Sayfadaki ek açıklama adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Açıklamayı boyamada kullanılacak sabit opaklık değerini alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Açıklama içeren sayfanın dizinini alır. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için açılır açıklama. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Açıklama dikdörtgenini alır veya ayarlar. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Bu annotation ile InReplyTo. tarafından belirtilen arasındaki ilişkiyi ("yanıt türü") belirten bir dize |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Açıklama açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption) { get; set; } | İçeriği belirleyen boole bayrağını alır veya ayarlar başlık olarak gösterilmelidir. |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting) { get; set; } | Çizginin başlangıç noktasını alır veya ayarlar. |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle) { get; set; } | Satır başlangıç noktası için satır bitiş stilini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Nesnenin açıklamasını temsil eden metni alır. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Açıklama için metin hizalamasını alır veya ayarlar. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Ek açıklamanın başlık çubuğunda görüntülenmesi gereken bir metni alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Açıklamanın genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept)(AnnotationSelector) | Ziyaretçiyi açıklama işlemeye kabul eder. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize)(Matrix) | Başlangıç ve Bitiş noktalarını matris dönüşümüne göre günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Bu örneği klonlar. Sanal yöntem. Her zaman null. döndür |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Açıklama içeriğini doğrudan sayfaya yerleştirir, açıklama nesnesi kaldırılır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Sayfa döndürmeyi dikkate alarak açıklamanın dikdörtgenini döndürür. |

### Ayrıca bakınız

* class [MarkupAnnotation](../markupannotation)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
