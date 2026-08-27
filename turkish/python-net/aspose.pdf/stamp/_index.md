---
title: "Stamp"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Alt sınıflar olarak gelen çeşitli damga türleri için soyut bir sınıf."
type: docs
weight: 1440
url: /tr/python-net/aspose.pdf/stamp/
---

## Stamp class

Alt sınıflar olarak gelen çeşitli damga türleri için soyut bir sınıf.

Stamp türü aşağıdaki üyeleri sunar:
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
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| put(page) | Sayfaya damga ekler. |
| set_stamp_id(value) | Damga kimliğini ayarlar. |
| get_stamp_id() | Damga kimliğini döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

