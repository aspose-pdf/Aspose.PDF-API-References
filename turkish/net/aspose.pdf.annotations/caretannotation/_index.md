---
title: Class CaretAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.CaretAnnotation sınıfı. Caret anotasyonunu temsil eden sınıf
type: docs
weight: 1560
url: /tr/net/aspose.pdf.annotations/caretannotation/
---
## CaretAnnotation sınıfı

Caret anotasyonunu temsil eden sınıf.

```csharp
public sealed class CaretAnnotation : MarkupAnnotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CaretAnnotation](caretannotation/#constructor)(Document) | Üreticide kullanılmak üzere yapıcı. |
| [CaretAnnotation](caretannotation/#constructor_1)(Page, Rectangle) | Belirtilen sayfada yeni bir Caret anotasyonu oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Anotasyon eylemlerinin listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut anotasyon görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/caretannotation/annotationtype/) { get; } | Anotasyonun türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Anotasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Anotasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Anotasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Anotasyon metnini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Anotasyonun oluşturulduğu tarih ve saati alır. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Anotasyonun bayrakları. |
| [Frame](../../aspose.pdf.annotations/caretannotation/frame/) { get; set; } | Caret dikdörtgenini alır veya ayarlar. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Anotasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Anotasyonun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf üreticisi için). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Bu anotasyonun "cevap verdiği" anotasyona bir referans. Her iki anotasyon da belgenin aynı sayfasında olmalıdır. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf üretimi için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Anotasyonun en son ne zaman değiştirildiğini gösteren tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki anotasyon adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Anotasyonu boyamak için kullanılacak sabit opaklık değerini alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Anotasyonu içeren sayfanın indeksini alır. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Bu anotasyonla ilişkili metni girmek veya düzenlemek için açılır anotasyon. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Anotasyon dikdörtgenini alır veya ayarlar. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Bu anotasyon ile InReplyTo tarafından belirtilen anotasyon arasındaki ilişkiyi (cevap türü) belirten bir dize. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Anotasyon açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Nesnenin tanımını temsil eden metni alır veya ayarlar. |
| [Symbol](../../aspose.pdf.annotations/caretannotation/symbol/) { get; set; } | Caret ile ilişkili sembolü alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Anotasyon için metin hizalamasını alır veya ayarlar. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Anotasyonun başlık çubuğunda görüntülenecek metni alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Anotasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/caretannotation/accept/)(AnnotationSelector) | Anotasyonu işlemek için ziyaretçi nesnesini kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Anotasyon için durumu ve durum modelini temizler. Örneğin, bir anotasyon için inceleme durumunu temizler. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Anotasyon içeriğini doğrudan sayfaya yerleştirir, anotasyon nesnesi kaldırılacaktır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak anotasyonun dikdörtgenini döndürür. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Anotasyonun durumunu alır. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Anotasyonun durum modelini alır. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Anotasyon için İşaretli ve İşaretsiz durumu ayarlar. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Bir anotasyon için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Durum, hedef anotasyonu oluşturan kullanıcı tarafından ayarlanır. Değer, hedef anotasyonun Başlık özelliğinden alınır. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Bir anotasyon için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |

### Ayrıca Bakınız

* sınıf [MarkupAnnotation](../markupannotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)