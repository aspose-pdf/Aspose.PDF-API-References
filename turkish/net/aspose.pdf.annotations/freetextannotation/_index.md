---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FreeTextAnnotation sınıfı. Sayfada doğrudan metin gösteren bir serbest metin notunu temsil eder. Sıradan bir metin notunun aksine, serbest metin notunun açık veya kapalı bir durumu yoktur; metin her zaman görünür.
type: docs
weight: 1810
url: /tr/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation sınıfı

Sayfada doğrudan metin gösteren bir serbest metin notunu temsil eder. Sıradan bir metin notunun aksine, serbest metin notunun açık veya kapalı bir durumu yoktur; metin her zaman görünür.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Üretici ile kullanılacak yapıcı. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Belirtilen sayfada yeni bir Serbest Metin notu oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Not eylemleri listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut not görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Not türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notun kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Çağrı çizgisini belirten nokta dizisi. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notun özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notun rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notun metnini alır veya ayarlar. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Notun oluşturulduğu tarih ve saati alır. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Metni biçimlendirmede kullanılacak varsayılan görünüm dizesini alır veya ayarlar. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Serbest Metin notunun varsayılan görünümünü temsil eden nesne. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Varsayılan bir stil dizesini alır veya ayarlar. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Çizgi sonlandırma noktası için çizgi sonlandırma stilini alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf üreticisi için). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Bu notun "cevap verdiği" notun referansı. Her iki not da belgenin aynı sayfasında olmalıdır. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Serbest metin notunun amacını alır veya ayarlar. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Notun metnini görüntülemede kullanılacak dördüncü (justification) biçimini belirten bir kod alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf üretimi için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notun adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Notu boyarken kullanılacak sabit opasite değerini alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Notu içeren sayfanın indeksini alır. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Bu notla ilişkili metni girmek veya düzenlemek için açılır not. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Notun dikdörtgenini alır veya ayarlar. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Bu not ile InReplyTo tarafından belirtilen not arasındaki ilişkiyi (cevap türü) belirten bir dize. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Not açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Notun döndürme açısını alır veya ayarlar. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Çizgi sonlandırma noktası için çizgi sonlandırma stilini alır veya ayarlar. Bu özellik kullanılmaz, lütfen EndingStyle kullanın. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notun görünüm sözlüğünü alır. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Nesnenin tanımını temsil eden metni alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Not için metin hizalamasını alır veya ayarlar. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | İki dikdörtgen arasındaki sayısal farkları tanımlayan dikdörtgen: Notun Rect girişi ve o dikdörtgenin içinde bulunan bir dikdörtgen. İç dikdörtgen, notun metninin görüntülenmesi gereken yerdir. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Görünümdeki metnin stilini alır veya ayarlar. Metin stili değiştiğinde, metin görünümü güncellenir. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Notun başlık çubuğunda görüntülenecek metni alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Notu işlemek için ziyaretçi nesnesini kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Not için durumu ve durum modelini temizler. Örneğin, bir not için inceleme durumunu temizler. Not, durum ve durum modeli anahtarlarına sahip diğer metin notlarında saklanır. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Not içeriğini doğrudan sayfaya yerleştirir, not nesnesi kaldırılacaktır. |
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