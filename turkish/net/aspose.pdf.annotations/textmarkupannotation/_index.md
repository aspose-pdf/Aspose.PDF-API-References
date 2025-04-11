---
title: Class TextMarkupAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.TextMarkupAnnotation sınıfı. Metin işaretleme notları için soyut temel sınıf
type: docs
weight: 2670
url: /tr/net/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation sınıfı

Metin işaretleme notları için soyut temel sınıf.

```csharp
public abstract class TextMarkupAnnotation : MarkupAnnotation
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Notların eylem listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut not görünüm durumunu alır veya ayarlar. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | Notun türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notun kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notun özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notun rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notun metnini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Notun oluşturulduğu tarih ve saati alır. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Bu notun "cevap verdiği" notun referansı. Her iki not da belgenin aynı sayfasında olmalıdır. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notun adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Notu boyamak için kullanılacak sabit opasite değerini alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Notu içeren sayfanın indeksini alır. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Bu notla ilişkili metni girmek veya düzenlemek için açılır not. |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints/) { get; set; } | Notun altında yatan metindeki kelime veya bitişik kelime gruplarının koordinatlarını belirten bir dizi nokta alır veya ayarlar. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Notun dikdörtgenini alır veya ayarlar. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Bu not ile InReplyTo tarafından belirtilen not arasındaki ilişkiyi (cevap türü) belirten bir dize. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Not açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notun görünüm sözlüğünü alır. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Nesnenin tanımını temsil eden metni alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Not için metin hizalamasını alır veya ayarlar. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Notun başlık çubuğunda görüntülenecek metni alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | Not işleme için ziyaretçiyi kabul eder. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize/)(Matrix) | QuadPoints'u matris dönüşümüne göre günceller. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Not için durumu ve durum modelini temizler. Örneğin, bir notun inceleme durumunu temizler. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği kopyalar. Sanal yöntem. Her zaman null döner. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Not içeriğini doğrudan sayfaya yerleştirir, not nesnesi kaldırılacaktır. |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext/)() | İşaretleme notunun altındaki metni dize olarak alır. |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments/)() | İşaretleme notunun altındaki metni [`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection/) olarak alır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notun dikdörtgenini döndürür. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Notun durumunu alır. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Notun durum modelini alır. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Not için İşaretli ve İşaretsiz durumu ayarlar. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Bir not için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Durum, hedef notu oluşturan kullanıcı tarafından ayarlanır. Değer, hedef notun Başlık özelliğinden alınır. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Bir not için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |

### Ayrıca Bakınız

* sınıf [MarkupAnnotation](../markupannotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)