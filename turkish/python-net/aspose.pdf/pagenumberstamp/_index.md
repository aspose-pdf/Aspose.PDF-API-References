---
title: "PageNumberStamp"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır."
type: docs
weight: 1140
url: /tr/python-net/aspose.pdf/pagenumberstamp/
---

## PageNumberStamp class

Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır.

PageNumberStamp türü aşağıdaki üyeleri ortaya koyar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PageNumberStamp(format) | PageNumberStamp sınıfının yeni bir örneğini başlatır |
| PageNumberStamp() | Yeni bir [PageNumberStamp](/pdf/python-net/aspose.pdf/pagenumberstamp/) sınıfı örneği başlatır. Format "#" olarak ayarlanmıştır. |
| PageNumberStamp(formatted_text) | PageNumberStamp sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| background | İçeriğin arka plan olarak damgalandığını gösteren bir bool değerini ayarlar veya alır.<br/>            Değer true ise, damga içeriği altta yer alır.<br/>            Varsayılan olarak, değer false ise, damga içeriği üstte yer alır. |
| opaklık | Damga opaklığını göstermek için bir değeri alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır.<br/>            Varsayılan olarak değer 1.0'dır. |
| outline_opacity | Damga kontur opaklığını göstermek için bir değeri alır veya ayarlar. Değer 0.0 ile 1.0 arasındadır.<br/>            Varsayılan olarak değer 1.0'dır. |
| outline_width | Damga kontur genişliğinin değerini alır veya ayarlar.<br/>            Varsayılan olarak değer 1.0'dır. |
| rotate | Damga içeriğinin dönüşünü [Rotation](/pdf/python-net/aspose.pdf/rotation/) değerlerine göre ayarlar veya alır.<br/> Not. Bu özellik, 90 derecenin katları (0, 90, 180, 270 derece) olan açıları ayarlamak içindir.<br/> Rastgele açı ayarlamak için RotateAngle özelliğini kullanın. <br/> Eğer ArbitraryAngle ile ayarlanan açı 90'ın katı değilse Rotate özelliği Rotation.None döndürür. |
| x_indent | Damganın yatay koordinatı, soldan başlayarak. |
| y_indent | Damganın dikey koordinatı, alttan başlayarak. |
| horizontal_alignment | Damganın sayfada yatay hizalamasını alır veya ayarlar. |
| vertical_alignment | Damganın sayfada dikey hizalamasını alır veya ayarlar. |
| left_margin | Damganın sol kenar boşluğunu alır veya ayarlar. |
| right_margin | Damganın sağ kenar boşluğunu alır veya ayarlar. |
| bottom_margin | Damganın alt kenar boşluğunu alır veya ayarlar. |
| top_margin | Damganın üst kenar boşluğunu alır veya ayarlar. |
| zoom_x | Damganın yatay yakınlaştırma faktörü. Damgayı yatay olarak ölçeklendirmeye izin verir. |
| genişlik | Sayfada damganın istenen genişliği. |
| yükseklik | Sayfada damganın istenen yüksekliği. |
| zoom_y | Damganın dikey yakınlaştırma faktörü. Damgayı dikey olarak ölçeklendirmeye izin verir. |
| zoom | Damganın yakınlaştırma faktörü. Damgayı ölçeklendirmeye izin verir.<br/> Lütfen ZoomX ve ZoomY özellik çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya izin verdiğini unutmayın. <br/> Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. <br/> Eğer ZoomX ve ZoomY farklıysa Zoom özelliği ZoomX değerini döndürür. |
| rotate_angle | Damganın derece cinsinden döndürme açısını alır veya ayarlar.<br/> Bu özellik, rastgele döndürme açısı ayarlamaya izin verir. |
| draw | Bu özellik, damganın sayfada nasıl çizildiğini belirler. Draw = true ise damga grafik operatörleri olarak çizilir ve draw = false ise damga metin olarak çizilir. |
| treat_y_indent_as_base_line | Metin yerleştirmek için koordinat başlangıcını tanımlar.<br/>            Eğer TreatYIndentAsBaseLine = true (Draw = true olduğunda varsayılan) YIndent değeri metin taban çizgisi olarak kabul edilir.<br/>            Eğer TreatYIndentAsBaseLine = false (Draw = false olduğunda varsayılan) YIndent değeri metnin alt (alçak çizgi) olarak kabul edilir. |
| word_wrap | Kelime kaydırmayı tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde birkaç satıra bölünür. Varsayılan değer: false. |
| justify | Metin hizalamasını tanımlar. Bu özellik true olarak ayarlanırsa, metnin hem sol hem sağ kenarları hizalanır. Varsayılan değer: false. |
| scale | Metnin ölçeklendirilmesini tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde ölçeklendirilir. |
| value | Sayfada damga olarak kullanılan dize değerini alır veya ayarlar. |
| text_state | Damganın metin özelliklerini alır. Ayrıntılar için [text_state](/pdf/python-net/aspose.pdf/textstamp/) sayfasına bakın. |
| text_alignment | Damganın içindeki metnin hizalaması. |
| max_row_width | WordWrap seçeneği için maksimum satır yüksekliği. |
| format | Sayfa numaralarını damgalamak için dize değeri. <br/>            Değer, damgalama sürecinde sayfa numarası ile değiştirilen '#' karakterini içermelidir. |
| starting_number | Başlangıç sayfasının numarasının değerini alır veya ayarlar. Diğer sayfalar bu değerden başlayarak numaralandırılacaktır. |
| numbering_style | Bu damga tarafından kullanılan numaralandırma stili. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| put(page) | Sayfa numarası ekler. |
| set_stamp_id(value) | Damga kimliğini ayarlar. |
| get_stamp_id() | Damga kimliğini döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

