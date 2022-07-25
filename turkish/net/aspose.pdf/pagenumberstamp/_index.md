---
title: PageNumberStamp
second_title: Aspose.PDF for .NET API Referansı
description: Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır.
type: docs
weight: 5890
url: /tr/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PageNumberStamp](pagenumberstamp#constructor)() | Yeni bir örneğini başlatır[`PageNumberStamp`](../pagenumberstamp) sınıf. Biçim "#" olarak ayarlandı. |
| [PageNumberStamp](pagenumberstamp#constructor_1)(FormattedText) | Biçimlendirilmiş metne göre SayfaNumarası Damgası oluşturur. |
| [PageNumberStamp](pagenumberstamp#constructor_2)(string) | Yeni bir örneğini başlatır[`PageNumberStamp`](../pagenumberstamp) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | İçeriğin arka plan olarak damgalandığını gösteren bir bool değeri ayarlar veya alır. Değer doğruysa, damga içeriği en alta yerleştirilir. Varsayılan olarak değer false'tur, damga içeriği en üste yerleştirilir. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Damganın alt kenar boşluğunu alır veya ayarlar. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Bu özellik, damganın sayfada nasıl çizileceğini belirler. Draw = true damga grafik operatörleri olarak çizilirse ve draw = false ise damga metin olarak çizilir. |
| [Format](../../aspose.pdf/pagenumberstamp/format) { get; set; } | Sayfa numaralarını damgalamak için dize değeri. Değer, damgalama sürecinde sayfa numarasıyla değiştirilen '#' karakterini içermelidir. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Sayfadaki damganın istenen yüksekliği. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Sayfadaki damganın Yatay hizalamasını alır veya ayarlar. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Metin yaslamayı tanımlar. Bu özellik true olarak ayarlanırsa metnin hem sol hem de sağ kenarları hizalanır. Varsayılan değer: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Damganın sol kenar boşluğunu alır veya ayarlar. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | WordWrap seçeneği için maksimum satır yüksekliği. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle) { get; set; } | Bu damga tarafından kullanılan numaralandırma stili. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Damga opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0. arasındadır Varsayılan olarak değer 1.0. 'dir |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Damga anahat opaklığını belirtmek için bir değer alır veya ayarlar. Değer 0.0 ile 1.0. arasındadır Varsayılan olarak değer 1.0. 'dir |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Damga anahat genişliğinin bir değerini alır veya ayarlar. Varsayılan olarak değer 1.0'dır. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Damganın sağ kenar boşluğunu alır veya ayarlar. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Damga içeriğinin dönüşünü buna göre ayarlar veya alır[`Rotation`](../rotation) değerler. Not. Bu özellik, 90 derecenin (0, 90, 180, 270 derece) katları olan açıları ayarlamak içindir. İsteğe bağlı açıyı ayarlamak için RotateAngle özelliğini kullanın. ArbitraryAngle tarafından ayarlanan açı 90'ın katı değilse, Rotate özelliği Rotation.None. değerini döndürür. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Derece olarak damganın döndürme açısını alır veya ayarlar. Bu özellik, isteğe bağlı döndürme açısının ayarlanmasına izin verir. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Metnin ölçeklenmesini tanımlar. Bu özellik true olarak ayarlanırsa ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde ölçeklenir. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber) { get; set; } | Başlangıç sayfası sayısının değerini alır veya ayarlar. Diğer sayfalar bu değerden başlayarak numaralandırılacaktır. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Damga içindeki metnin hizalanması. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Damganın metin özelliklerini alır. Görmek[`TextState`](../textstamp/textstate) ayrıntılar için. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Damganın üst kenar boşluğunu alır veya ayarlar. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Metni yerleştirmek için koordinat kaynağını tanımlar. TreatYIndentAsBaseLine = true ise (Çizim = true olduğunda varsayılan) YIndent değeri metin taban çizgisi olarak değerlendirilir. TreatYIndentAsBaseLine = false (Çizim = false olduğunda varsayılan) YIndent değeri alt olarak kabul edilir ( iniş çizgisi) metni. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Sayfada damga olarak kullanılan dize değerini alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Sayfadaki damganın dikey hizalamasını alır veya ayarlar. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Sayfadaki damganın istenen genişliği. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Sözcük kaydırmayı tanımlar. Bu özellik true olarak ayarlanırsa ve Width değeri belirtilirse, metin belirtilen genişliğe sığması için birkaç satırda bölünür. Varsayılan değer: false. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Soldan başlayarak yatay damga koordinatı. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Alttan başlayarak dikey damga koordinatı. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Damganın yakınlaştırma faktörü. Damganın ölçeklenmesine izin verir. ZoomX ve ZoomY özelliklerinin her bir eksen için ayrı ayrı yakınlaştırma faktörü ayarlamasına izin verdiğini lütfen unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. ZoomX ve ZoomY farklıysa Zoom özelliği ZoomX değerini döndürür. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Damganın yatay yakınlaştırma faktörü. Damganın yatay olarak ölçeklenmesini sağlar. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Damganın dikey yakınlaştırma faktörü. Damgayı dikey olarak ölçeklendirmeye izin verir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Damga kimliğini döndürür. |
| override [Put](../../aspose.pdf/pagenumberstamp/put)(Page) | Sayfa numarası ekler. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Damga kimliğini ayarlar. |

### Ayrıca bakınız

* class [TextStamp](../textstamp)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
