---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RedactionAnnotation sınıfı. Redact anotasyonunu temsil eder
type: docs
weight: 2400
url: /tr/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation sınıfı

Redact anotasyonunu temsil eder.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | RedactionAnnotation için yapıcı. Üreticide kullanmak için. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | RedactAnnotation için yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Anotasyon eylemlerinin listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut anotasyon görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Anotasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Anotasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Redaksiyon aktif olmadığında çizilen kenarlığın rengini alır veya ayarlar. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Anotasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Anotasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Anotasyon metnini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Anotasyonun oluşturulduğu tarih ve saati alır. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır veya ayarlar. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Anotasyonu doldurmak için rengi alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Anotasyonun bayrakları. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | OverlayText için yazı tipi boyutunu alır veya ayarlar. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Anotasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Anotasyonun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça hiperlinkini alır veya ayarlar (pdf üreticisi için). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Bu anotasyonun "cevap verdiği" anotasyona bir referans. Her iki anotasyon da belgenin aynı sayfasında olmalıdır. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf üretimi için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Anotasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki anotasyon adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Anotasyonu boyamak için kullanılacak sabit opaklık değerini alır veya ayarlar. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Redaksiyon anotasyonunda basılacak metni alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Anotasyonu içeren sayfanın indeksini alır. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Bu anotasyonla ilişkili metni girmek veya düzenlemek için açılır anotasyon. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayılar dizisi. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Anotasyon dikdörtgenini alır veya ayarlar. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Eğer true ise, overlay metni anotasyonda tekrar edilecektir. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Bu anotasyon ile InReplyTo tarafından belirtilen anotasyon arasındaki ilişkiyi ( "cevap türü") belirten bir dize. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Anotasyon açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Nesnenin tanımını temsil eden metni alır veya ayarlar. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Overlay Metninin hizalamasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Anotasyon için metin hizalamasını alır veya ayarlar. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Anotasyonun başlık çubuğunda görüntülenecek metni alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Anotasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Anotasyonu işlemek için ziyaretçi nesnesini kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Anotasyon için durumu ve durum modelini temizler. Örneğin, bir anotasyon için inceleme durumunu temizler. Not, durumun diğer metin anotasyonlarında saklandığıdır; bu anotasyonların durum ve durum modeli anahtarları vardır. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği kopyalar. Sanal yöntem. Her zaman null döner. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Anotasyonu düzleştirir, yani anotasyonu kaldırır ve onun yerine ekler |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak anotasyonun dikdörtgenini döndürür. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Anotasyonun durumunu alır. Not, durumun diğer metin anotasyonlarında saklandığıdır; bu anotasyonların durum ve durum modeli anahtarları vardır. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Anotasyonun durum modelini alır. Not, durumun diğer metin anotasyonlarında saklandığıdır; bu anotasyonların durum ve durum modeli anahtarları vardır. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Anotasyonu düzleştirir ve sayfa içeriğini redakte eder (yani, redakte edilmiş anotasyonun altındaki metin ve resmi kaldırır) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Anotasyon için İşaretli ve İşaretsiz durumu ayarlar. Not, durumun diğer metin anotasyonlarında saklandığıdır; bu anotasyonların durum ve durum modeli anahtarları vardır. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Bir anotasyon için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Durum, hedef anotasyonu oluşturan kullanıcı tarafından ayarlanır. Değer, hedef anotasyonun Başlık özelliğinden alınır. Not, durumun diğer metin anotasyonlarında saklandığıdır; bu anotasyonların durum ve durum modeli anahtarları vardır. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Bir anotasyon için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Not, durumun diğer metin anotasyonlarında saklandığıdır; bu anotasyonların durum ve durum modeli anahtarları vardır. |

### Ayrıca Bakınız

* sınıf [MarkupAnnotation](../markupannotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)