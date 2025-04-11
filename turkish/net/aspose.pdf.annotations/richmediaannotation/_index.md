---
title: Class RichMediaAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RichMediaAnnotation sınıfı. Sınıf, PDF belgesine video/ses verilerini gömmeye olanak tanıyan RichMediaAnnotation'ı tanımlar.
type: docs
weight: 2480
url: /tr/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation Sınıfı

Sınıf, PDF belgesine video/ses verilerini gömmeye olanak tanıyan RichMediaAnnotation'ı tanımlar.

```csharp
public class RichMediaAnnotation : Annotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Sayfa, Dikdörtgen) | RichMediaAnnotation'ı başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Notasyon eylemleri listesini alır. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | Uygulamayı etkinleştiren olay. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut notasyon görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | Notasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notasyon rengini alır veya ayarlar. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | Zengin Medya içeriğinin verisi. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notasyon metnini alır veya ayarlar. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | Oyuncuya geçirilen flash değişkenlerini ayarlar veya alır. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | Video/ses verilerini oynatmak için özel flash oynatıcıyı ayarlar veya alır. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notasyonun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notasyonun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parçanın köprü bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notasyon adını alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Notasyonu içeren sayfanın indeksini alır. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Notasyon dikdörtgenini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Notasyon için metin hizalamasını alır veya ayarlar. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | İçerik türünü alır veya ayarlar. Olası değerler: Ses, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip bir grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(NotasyonSeçici) | Bu notasyon için ziyaretçiyi kabul eder. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Akış) | Özel adlandırılmış veri ekler (örneğin, flash script için gereklidir). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matris) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği kopyalar. Sanal yöntem. Her zaman null döner. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Notasyon içeriğini doğrudan sayfaya yerleştirir, notasyon nesnesi kaldırılacaktır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notasyonun dikdörtgenini döndürür. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Akış) | İçerik akışını ayarlar. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Akış) | Notasyonun posterini ayarlar. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | Belirtilen parametrelerle verileri günceller. |

## Diğer Üyeler

| İsim | Açıklama |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | Notasyonu etkinleştiren olay. |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | Multimedya türü. |

### Ayrıca Bakınız

* sınıf [Notasyon](../annotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)