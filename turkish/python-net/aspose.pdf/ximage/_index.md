---
title: "XImage"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Görüntü X-Object'i temsil eden sınıf."
type: docs
weight: 1680
url: /tr/python-net/aspose.pdf/ximage/
---

## XImage class

Görüntü X-Object'i temsil eden sınıf.

XImage türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| contains_transparency | Görüntü şeffaflık içeriyorsa true döndürür; aksi takdirde false. |
| grayscaled | Görüntünün gri tonlamalı sürümünü alır. |
| filter_type | Görüntü filtre tipini alır. |
| genişlik | Görüntünün genişliğini alır. |
| yükseklik | Görüntünün yüksekliğini alır. |
| name | Görüntü adını alır veya ayarlar. Lütfen, sayfa içeriklerinde referansları olan bir görüntünün adını değiştirirseniz belgenin hatalı olabileceğini unutmayın. Bu durumda XImage.Rename yöntemini kullanın. |
| metadata | Görüntünün meta verileri. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| save(stream) | Görüntü verilerini akışa JPEG görüntüsü olarak kaydeder. |
| save(stream, format) | Görüntüyü istenen formatta akışa kaydeder. |
| save(stream, resolution) | Görüntü verilerini belirtilen çözünürlükte JPEG görüntüsü olarak akışa kaydeder. |
| save(stream, format, resolution) | Görüntüyü istenen formatta ve belirtilen çözünürlükte akışa kaydeder. |
| rename(name) | Görüntünün adını değiştirir ve görüntüye yapılan tüm referansları yeni adla değiştirir. |
| get_color_type() | Görüntünün renk tipini döndürür. |
| detect_color_type(bmp) | Görüntünün renk tipini döndürür. |
| is_the_same_object(image) | Her iki görüntü aynı nesneye referans veriyorsa true döndürür. |
| get_name_in_collection() | Görüntünün ints koleksiyonundaki adını döndürür. |
| to_stream() | Orijinal görüntü akışını döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

