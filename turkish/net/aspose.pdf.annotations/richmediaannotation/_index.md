---
title: RichMediaAnnotation
second_title: Aspose.PDF for .NET API Referansı
description: Sınıfı video/ses verilerini PDF belgesine yerleştirmeye izin veren RichMediaAnnotationı açıklar.
type: docs
weight: 1030
url: /tr/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

Sınıfı, video/ses verilerini PDF belgesine yerleştirmeye izin veren RichMediaAnnotation'ı açıklar.

```csharp
public class RichMediaAnnotation : Annotation
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation)(Page, Rectangle) | RichMediaAnnotation'ı başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Açıklama eylemlerinin listesini alır. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon) { get; set; } | Uygulamayı etkinleştiren olay. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Geçerli ek açıklama görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype) { get; } | Açıklama türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Açıklama kenarlığı özelliklerini alır veya ayarlar.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Açıklama özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Açıklama rengini alır veya ayarlar. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content) { get; } | Zengin Medya içeriğinin verileri. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ek açıklama metnini alır veya ayarlar. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables) { get; set; } | Oynatıcıya iletilen flash değişkenlerini ayarlar veya alır. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer) { get; set; } | Video/ses verilerini oynatmak için özel flash oynatıcı ayarlar veya alır. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Ek açıklamanın bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Açıklamanın tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Açıklamanın yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Açıklamanın yakın zamanda değiştirildiği tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Sayfadaki ek açıklama adını alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Açıklama içeren sayfanın dizinini alır. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Açıklama dikdörtgenini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Açıklama için metin hizalamasını alır veya ayarlar. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type) { get; set; } | İçerik türünü alır veya ayarlar. Olası değerler: Ses, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Açıklamanın genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept)(AnnotationSelector) | Bu ek açıklama için ziyaretçi kabul eder. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata)(string, Stream) | Özel adlandırılmış veri ekleyin (örneğin flash komut dosyası için gereklidir). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü güncelleyin. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Bu örneği klonlar. Sanal yöntem. Her zaman null. döndür |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Açıklama içeriğini doğrudan sayfaya yerleştirir, açıklama nesnesi kaldırılır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Sayfa döndürmeyi dikkate alarak açıklamanın dikdörtgenini döndürür. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent)(string, Stream) | İçerik akışını ayarlayın. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter)(Stream) | Açıklamanın posterini ayarlayın. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update)() | Belirtilen parametrelerle verileri günceller. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| enum [ActivationEvent](richmediaannotation.activationevent) | Açıklamayı etkinleştiren olay. |
| enum [ContentType](richmediaannotation.contenttype) | Multimedya türü. |

### Ayrıca bakınız

* class [Annotation](../annotation)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
