---
title: Class WidgetAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.WidgetAnnotation sınıfı. Widget anotasyonunu temsil eden sınıf
type: docs
weight: 2720
url: /tr/net/aspose.pdf.annotations/widgetannotation/
---
## WidgetAnnotation sınıfı

Widget anotasyonunu temsil eden sınıf.

```csharp
public class WidgetAnnotation : Annotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [WidgetAnnotation](widgetannotation/)(Document) | Anotasyon oluşturur (Generator için kullanılır) |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Anotasyon eylemlerini alır. (2 özellik) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut anotasyon görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Anotasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Anotasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Anotasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Anotasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Anotasyon metnini alır veya ayarlar. |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Anotasyonun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Anotasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Anotasyonun yüksekliğini alır veya ayarlar. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Anotasyon vurgulama modunu alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış marjı alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Anotasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki anotasyon adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Anotasyon etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Anotasyonu içeren sayfanın indeksini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Anotasyonun üst öğesini alır. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Anotasyon dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Anotasyon için metin hizalamasını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Anotasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Ziyaretçiyi kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Parametreleri ve görünümü, matris dönüşümüne göre günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu sağlanan akıma yazar. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu belirtilen dosyaya yazar. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Anotasyon içeriğini doğrudan sayfaya yerleştirir, anotasyon nesnesi kaldırılacaktır. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mevcut durum adlarına göre "kontrol edilmiş" durumunun adını döner. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak anotasyonun dikdörtgenini döner. |

### Ayrıca Bakınız

* sınıf [Annotation](../annotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)