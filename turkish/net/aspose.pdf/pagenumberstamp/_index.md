---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageNumberStamp sınıfı. Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır.
type: docs
weight: 8230
url: /tr/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp sınıfı

Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | `PageNumberStamp` sınıfının yeni bir örneğini başlatır. Format "#"' olarak ayarlanmıştır. |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Biçimlendirilmiş metin ile PageNumberStamp oluşturur. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | `PageNumberStamp` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Yazı tipi boyutu hassasiyetini otomatik olarak ayarlar. Varsayılan değer: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Etkinleştirildiğinde, yazı tipi boyutu damga dikdörtgenine sığacak şekilde otomatik olarak ayarlanır: [`Width`](../textstamp/width/) ve [`Height`](../textstamp/height/). Varsayılan genişlik ve yükseklik sayfa dikdörtgeninden türetilir. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | İçeriğin arka plan olarak damgalanıp damgalanmadığını belirten bir bool değeri ayarlar veya alır. Değer true ise, damga içeriği en alta yerleştirilir. Varsayılan olarak, değer false'tur, damga içeriği en üste yerleştirilir. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Damganın alt kenar boşluğunu alır veya ayarlar. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Bu özellik, damganın sayfada nasıl çizileceğini belirler. Eğer Draw = true ise damga grafik operatörleri olarak çizilir ve eğer draw = false ise damga metin olarak çizilir. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Damga yerleştirildikten sonraki gerçek yazı tipi boyutu. ('AutoAdjustFontSizeToFitStampRectangle' seçeneği etkinleştirildiğinde, yapıcıda sağlanan başlangıç yazı tipi boyutundan farklı olabilir.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Sayfa numaralarını damgalamak için kullanılan dize değeri. Değer, damgalama sürecinde sayfa numarası ile değiştirilen '#' karakterini içermelidir. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Sayfadaki damganın istenen yüksekliği. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Damganın sayfadaki yatay hizalamasını alır veya ayarlar. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Metin hizalamasını tanımlar. Bu özellik true olarak ayarlandığında, metnin hem sol hem de sağ kenarları hizalanır. Varsayılan değer: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Damganın sol kenar boşluğunu alır veya ayarlar. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap seçeneği için maksimum satır yüksekliği. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | İstenilen karakterleri içermeyen yazı tipleri durumunda davranışı tanımlayan modu alır veya ayarlar. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Bu damga tarafından kullanılan numaralandırma stili. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Damga opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Damga dış hat opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Damga dış hat genişliğinin değerini alır veya ayarlar. Varsayılan değer 1.0'dır. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Kullanıcı yazı tipi gerekli karakteri içermediğinde kullanılacak yazı tipini alır veya ayarlar. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Damganın sağ kenar boşluğunu alır veya ayarlar. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Damga içeriğinin [`Rotation`](../rotation/) değerlerine göre döndürülmesini ayarlar veya alır. Not: Bu özellik, 90 derece (0, 90, 180, 270 derece) katları olan açıları ayarlamak içindir. Keyfi bir açı ayarlamak için RotateAngle özelliğini kullanın. Eğer KeyfiAçı ile ayarlanan açı 90'ın katı değilse, Rotate özelliği Rotation.None döner. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Damganın derece cinsinden döndürme açısını alır veya ayarlar. Bu özellik, keyfi bir döndürme açısı ayarlamaya olanak tanır. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Metnin ölçeklendirilmesini tanımlar. Bu özellik true olarak ayarlandığında ve Genişlik değeri belirtilmişse, metin belirtilen genişliğe sığacak şekilde ölçeklendirilir. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Başlangıç sayfasının numarasının değerini alır veya ayarlar. Diğer sayfalar bu değerden başlayarak numaralandırılacaktır. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Damga içindeki metnin hizalamasını alır veya ayarlar. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Damganın metin özelliklerini alır. Ayrıntılar için [`TextState`](../textstamp/textstate/) bölümüne bakın. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Damganın üst kenar boşluğunu alır veya ayarlar. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Metni yerleştirmek için koordinat kökenini tanımlar. Eğer TreatYIndentAsBaseLine = true (Draw = true olduğunda varsayılan) ise YIndent değeri metin taban çizgisi olarak kabul edilir. Eğer TreatYIndentAsBaseLine = false (Draw = false olduğunda varsayılan) ise YIndent değeri metnin altı (iniş çizgisi) olarak kabul edilir. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Sayfada damga olarak kullanılan dize değerini alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Sayfadaki damganın dikey hizalamasını alır veya ayarlar. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Sayfadaki damganın istenen genişliği. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Metin işleme için kelime sarma modunu alır veya ayarlar. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Soldan başlayarak yatay damga koordinatı. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Aşağıdan başlayarak dikey damga koordinatı. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Damganın yakınlaştırma faktörü. Damgayı ölçeklendirmeye olanak tanır. Lütfen ZoomX ve ZoomY çiftinin her eksen için ayrı ayrı yakınlaştırma faktörünü ayarlamaya izin verdiğini unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. Eğer ZoomX ve ZoomY farklıysa, Zoom özelliği ZoomX değerini döner. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Damganın yatay yakınlaştırma faktörü. Damgayı yatay olarak ölçeklendirmeye olanak tanır. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Damganın dikey yakınlaştırma faktörü. Damgayı dikey olarak ölçeklendirmeye olanak tanır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Damga kimliğini döner. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Sayfa numarasını ekler. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Damga kimliğini ayarlar. |

### Ayrıca Bakınız

* sınıf [TextStamp](../textstamp/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)