---
title: RedactionAnnotation
second_title: Aspose.PDF for .NET API Referansı
description: Redact ek açıklamasını temsil eder.
type: docs
weight: 960
url: /tr/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

Redact ek açıklamasını temsil eder.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [RedactionAnnotation](redactionannotation#constructor)(Document) | Redaksiyon Açıklaması için Oluşturucu. Jeneratörde kullanmak için. |
| [RedactionAnnotation](redactionannotation#constructor_1)(Page, Rectangle) | RedactAnnotation için Oluşturucu. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Açıklama eylemlerinin listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Geçerli ek açıklama görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype) { get; } | Açıklama türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Açıklama kenarlığı özelliklerini alır veya ayarlar.[`Border`](../annotation/border) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor) { get; set; } | Redaksiyon etkin olmadığında çizilen kenarlığın rengini alır veya ayarlar. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Açıklama özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Açıklama rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ek açıklama metnini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Açıklamanın oluşturulduğu tarih ve saati alır. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance) { get; set; } | Metni biçimlendirmede kullanılacak varsayılan görünüm dizesini alır veya ayarlar. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor) { get; set; } | Ek açıklamayı doldurmak için rengi alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Ek açıklamanın bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Açıklamanın tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Açıklamanın yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Bu ek açıklamanın "yanıt olarak" olduğu ek açıklama referansı. Her iki ek açıklama da belgenin aynı sayfasında olmalıdır. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Açıklamanın yakın zamanda değiştirildiği tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Sayfadaki ek açıklama adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Açıklamayı boyamada kullanılacak sabit opaklık değerini alır veya ayarlar. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext) { get; set; } | Redaksiyon ek açıklamasına yazdırılacak metin. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Açıklama içeren sayfanın dizinini alır. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için açılır açıklama. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint) { get; set; } | Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayıdan oluşan bir dizi. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Açıklama dikdörtgenini alır veya ayarlar. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat) { get; set; } | Doğruysa bindirme metni ek açıklamada tekrarlanacak. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Bu annotation ile InReplyTo. tarafından belirtilen arasındaki ilişkiyi ("yanıt türü") belirten bir dize |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Açıklama açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Nesnenin açıklamasını temsil eden metni alır. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment) { get; set; } | Alır veya ayarlar. Yer Paylaşımlı Metnin Hizalanması. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Açıklama için metin hizalamasını alır veya ayarlar. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Ek açıklamanın başlık çubuğunda görüntülenmesi gereken bir metni alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Açıklamanın genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept)(AnnotationSelector) | Ek açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü güncelleyin. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Bu örneği klonlar. Sanal yöntem. Her zaman null. döndür |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten)() | Açıklamayı düzleştirir, yani açıklamayı kaldırır ve its ekler |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Sayfa döndürmeyi dikkate alarak açıklamanın dikdörtgenini döndürür. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact)() | Ek açıklamayı düzleştirir ve sayfa içeriğini yeniden düzenler (yani, düzeltilmiş ek açıklama altındaki metni ve resmi kaldırır) |

### Ayrıca bakınız

* class [MarkupAnnotation](../markupannotation)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
