---
title: "Dikdörtgen"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sınıf, dikdörtgeni temsil eder."
type: docs
weight: 1320
url: /tr/python-net/aspose.pdf/rectangle/
---

## Rectangle class

Sınıf, dikdörtgeni temsil eder.

Dikdörtgen türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Rectangle sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| genişlik | Dikdörtgenin genişliği. |
| yükseklik | Dikdörtgenin yüksekliği. |
| llx | Alt sol köşenin X koordinatı. |
| lly | Alt sol köşenin Y koordinatı. |
| urx | Üst sağ köşenin X koordinatı. |
| ury | Üst sağ köşenin Y koordinatı. |
| basit | Sıfır konum ve boyuta sahip basit bir dikdörtgen başlatır. |
| is_trivial | Dikdörtgenin trivial olup olmadığını, yani sıfır boyut ve konuma sahip olup olmadığını kontrol eder. |
| is_empty | Dikdörtgenin boş olup olmadığını kontrol eder. |
| is_point | Dikdörtgenin nokta olup olmadığını, yani LLX'in URX'e ve LLY'in URY'e eşit olup olmadığını kontrol eder. |
| empty | Boş dikdörtgen |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| rotate(angle) | Dikdörtgeni belirtilen açıyla döndür. |
| rotate(angle) | Dikdörtgeni belirtilen açıyla döndür. |
| to_rect() | Dikdörtgeni System.Drawing.Rectangle örneğine dönüştürür. Ondalıklı konum ve boyutlar kırpılır. |
| from_rect(src) | Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır. |
| parse(value) | Dizgiyi ayrıştırmayı deneyip içinden dikdörtgen bileşenleri llx, lly, urx, ury çıkarır. |
| equals(other) | Dikdörtgenlerin aynı konuma ve boyuta sahip olup olmadığını, yani eşit olup olmadığını kontrol eder. |
| near_equals(other, delta) | Dikdörtgenlerin yakın eşit olup olmadığını, yani (delta kadar) yakın aynı konuma ve boyuta sahip olup olmadığını kontrol eder. |
| intersect(other_rect) | İki dikdörtgenle kesişir. |
| join(other_rect) | Dikdörtgenleri birleştirir. |
| is_intersect(other_rect) | Bu dikdörtgenin diğer dikdörtgenle kesişip kesişmediğini belirler. |
| contains(point) | Verilen noktanın dikdörtgenin içinde olup olmadığını belirler. |
| center() | Dikdörtgenin merkez koordinatlarını döndürür. |
| clone() | Rectangle nesnesinin bir kopyasını oluşturur. |
| to_points() | Dikdörtgeni nokta dizisine ("QuadPoints") dönüştürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

