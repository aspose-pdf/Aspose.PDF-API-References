---
title: "ImageStamp"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Grafik damgasını temsil eder."
type: docs
weight: 690
url: /tr/python-net/aspose.pdf/imagestamp/
---

## ImageStamp class

Grafik damgasını temsil eder.

ImageStamp türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| ImageStamp(image) | ImageStamp sınıfının yeni bir örneğini başlatır |
| ImageStamp(file_name) | ImageStamp sınıfının yeni bir örneğini başlatır |
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
| genişlik | Görüntü genişliğini alır veya ayarlar. Bu özelliği ayarlamak, görüntüyü yatay olarak ölçeklendirmeyi sağlar. |
| yükseklik | Görüntü yüksekliğini alır veya ayarlar. Bu özelliği ayarlamak, görüntüyü dikey olarak ölçeklendirmeyi sağlar. |
| zoom_y | Damganın dikey yakınlaştırma faktörü. Damgayı dikey olarak ölçeklendirmeye izin verir. |
| zoom | Damganın yakınlaştırma faktörü. Damgayı ölçeklendirmeye izin verir.<br/> Lütfen ZoomX ve ZoomY özellik çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya izin verdiğini unutmayın. <br/> Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. <br/> Eğer ZoomX ve ZoomY farklıysa Zoom özelliği ZoomX değerini döndürür. |
| rotate_angle | Damganın derece cinsinden döndürme açısını alır veya ayarlar.<br/> Bu özellik, rastgele döndürme açısı ayarlamaya izin verir. |
| image | Damgalama için kullanılan görüntü akışını alır. |
| kalite | Görüntü damgasının kalitesini yüzde olarak alır veya ayarlar. Geçerli değerler 0..100%. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| put(page) | Sayfaya grafik damga ekler. |
| set_stamp_id(value) | Damga kimliğini ayarlar. |
| get_stamp_id() | Damga kimliğini döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

