---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox sınıfı.
type: docs
weight: 4870
url: /tr/net/aspose.pdf/floatingbox/
---
## FloatingBox sınıfı

```csharp
public class FloatingBox : BaseParagraph
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | `FloatingBox` sınıfının yeni bir örneğini başlatır. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Belirtilen genişlik ve yükseklik ile `FloatingBox` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Yüzen kutunun arka plan rengini belirten bir [`Color`](../color/) nesnesini alır veya ayarlar. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Sayfa için arka plan resmini alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Yüzen kutunun kenar bilgilerini belirten bir [`BorderInfo`](../borderinfo/) nesnesini alır veya ayarlar. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Bir sütun bilgisi alır veya ayarlar. |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Yüzen kutunun yüksekliğini belirten bir float değerini alır veya ayarlar. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Paragrafın yatay hizalamasını alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Paragrafın bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Paragrafın bir sonraki sayfada tekrarlanıp tekrarlanmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan değer false'dur. Bu özellik yalnızca paragrafın kendisi ve ReferansParagraphID'sinin atıfta bulunduğu nesne RepeatingRows içinde yer aldığında geçerlidir. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Tablo sol koordinatını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için). |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Yüzen kutunun iç boşluğunu belirten bir [`MarginInfo`](../margininfo/) nesnesini alır veya ayarlar. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Hücredeki tüm paragrafları belirten bir [`Paragraphs`](./paragraphs/) koleksiyonunu alır veya ayarlar. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Yüzen kutunun sayfadaki konumunu belirlemek için varyantı belirtir. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Tablo üst koordinatını alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Yüzen kutunun genişliğini belirten bir float değerini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Yeni bir `FloatingBox` nesnesini klonlar. Yüzen kutudaki paragraflar klonlanmaz. |

### Ayrıca Bakınız

* sınıf [BaseParagraph](../baseparagraph/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)