---
title: Annotation
second_title: Aspose.PDF for .NET API Referansı
description: Açıklama nesnesini temsil eden sınıf.
type: docs
weight: 80
url: /tr/net/aspose.pdf.annotations/annotation/
---
## Annotation class

Açıklama nesnesini temsil eden sınıf.

```csharp
public abstract class Annotation : BaseParagraph
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Açıklama eylemlerinin listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Geçerli ek açıklama görünüm durumunu alır veya ayarlar. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype) { get; } | Açıklama türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Açıklama kenarlığı özelliklerini alır veya ayarlar.[`Border`](./border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Açıklama özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Açıklama rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ek açıklama metnini alır veya ayarlar. |
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
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Açıklamanın genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert) { get; set; } | Doğruysa, KM belgesi görüntüye dönüştürülmeden önce açıklama görünümü güncellenecektir. Bu, alanların doğru şekilde dönüştürülmesine izin verir, ancak muhtemelen daha fazla zaman gerektirir. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset) { get; set; } | Bu özellik true olarak ayarlanırsa, yazı tipleri belgeye alt kümeler olarak eklenecektir. Varsayılan değer true. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept)(AnnotationSelector) | Ek açıklama işleme için ziyaretçiyi kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü güncelleyin. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Bu örneği klonlar. Sanal yöntem. Her zaman null. döndür |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Açıklama içeriğini doğrudan sayfaya yerleştirir, açıklama nesnesi kaldırılır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Sayfa döndürmeyi dikkate alarak açıklamanın dikdörtgenini döndürür. |

### Ayrıca bakınız

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
