---
title: Class WatermarkAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.WatermarkAnnotation sınıfı. Sınıf, Watermark notu nesnesini tanımlar
type: docs
weight: 2710
url: /tr/net/aspose.pdf.annotations/watermarkannotation/
---
## WatermarkAnnotation sınıfı

Sınıf, Watermark notu nesnesini tanımlar.

```csharp
public class WatermarkAnnotation : Annotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [WatermarkAnnotation](watermarkannotation/)(Sayfa, Dikdörtgen) | Watermark notu sınıfı için yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Not eylemleri listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut not görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/watermarkannotation/annotationtype/) { get; } | Not türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notun kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notun özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notun rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notun metnini alır veya ayarlar. |
| [FixedPrint](../../aspose.pdf.annotations/watermarkannotation/fixedprint/) { get; } | Watermark notunun sabit baskı nesnesi. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parçanın köprü bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notun adını alır veya ayarlar. |
| [Opacity](../../aspose.pdf.annotations/watermarkannotation/opacity/) { get; set; } | Notun opaklığını alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Notu içeren sayfanın indeksini alır. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Notun dikdörtgenini alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notun görünüm sözlüğünü alır. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Not için metin hizalamasını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/watermarkannotation/accept/)(AnnotationSelector) | Not için ziyaretçi uygula. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/watermarkannotation/changeafterresize/)(Matrix) | Boş bir gövde ile temel sınıftaki tanımı geçersiz kılar. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Not içeriğini doğrudan sayfaya yerleştirir, not nesnesi kaldırılacaktır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notun dikdörtgenini döndürür. |
| [SetText](../../aspose.pdf.annotations/watermarkannotation/settext/)(FormattedText) | Notun metnini ayarlar. |
| [SetTextAndState](../../aspose.pdf.annotations/watermarkannotation/settextandstate/)(string[], TextState) | Notun metnini ayarlar. |

### Ayrıca Bakınız

* sınıf [Annotation](../annotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)