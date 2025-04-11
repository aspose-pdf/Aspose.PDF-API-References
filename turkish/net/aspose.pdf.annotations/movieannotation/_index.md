---
title: Class MovieAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.MovieAnnotation sınıfı. Bilgisayar ekranında ve hoparlörler aracılığıyla sunulacak animasyonlu grafikler ve ses içeren bir film anotasyonunu temsil eder. Anotasyon etkinleştirildiğinde film oynatılır.
type: docs
weight: 2110
url: /tr/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation sınıfı

Bilgisayar ekranında ve hoparlörler aracılığıyla sunulacak animasyonlu grafikler ve ses içeren bir film anotasyonunu temsil eder. Anotasyon etkinleştirildiğinde film oynatılır.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Üretici ile kullanılmak üzere yapıcı. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Belirtilen sayfada yeni bir Ses anotasyonu oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Anotasyon eylemlerinin listesini alır. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut anotasyon görünüm durumunu alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Anotasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Filmin sınırlayıcı kutusunun genişliğini ve yüksekliğini piksel cinsinden alır veya ayarlar. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Anotasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Anotasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Anotasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Anotasyon metnini alır veya ayarlar. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Kendini tanımlayan bir film dosyasını tanımlayan bir dosya spesifikasyonunu alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Anotasyonun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Anotasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Anotasyonun yüksekliğini alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf üreticisi için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf üretimi için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Anotasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki anotasyon adını alır veya ayarlar. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Anotasyonu içeren sayfanın indeksini alır. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Filmi temsil eden bir poster resminin nasıl ve ne zaman görüntüleneceğini belirten bir bayrak veya akış alır veya ayarlar. Eğer true ise, poster resmi film dosyasından alınacaktır; false ise, poster görüntülenmeyecektir. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Anotasyon dikdörtgenini alır veya ayarlar. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Filmin sayfaya göre saat yönünde kaç derece döneceğini alır veya ayarlar. Değer 90'ın katı olmalıdır. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Anotasyon için metin hizalamasını alır veya ayarlar. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Film anotasyonunun başlığını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Anotasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Anotasyonu işlemek için ziyaretçi nesnesini kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği kopyalar. Sanal yöntem. Her zaman null döner. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Anotasyon içeriğini doğrudan sayfaya yerleştirir, anotasyon nesnesi kaldırılacaktır. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak anotasyonun dikdörtgenini döndürür. |

### Ayrıca Bakınız

* sınıf [Annotation](../annotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)