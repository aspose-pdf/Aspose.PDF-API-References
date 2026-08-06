---
title: "Matrix"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sınıf dönüşüm matrisini temsil eder."
type: docs
weight: 900
url: /tr/python-net/aspose.pdf/matrix/
---

## Matrix class

Sınıf dönüşüm matrisini temsil eder.

Matrix türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Matrix() | Constructor<br/>            standart 1'e 1 matris oluşturur:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Matrix sınıfının yeni bir örneğini başlatır |
| Matrix(matrix_array) | Matrix sınıfının yeni bir örneğini başlatır |
| Matrix(matrix) | Matrix sınıfının yeni bir örneğini başlatır |
| Matrix(a, b, c, d, e, f) | Matrix sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| data | Matrix verilerini dizi olarak alır. |
| a | Dönüşüm matrisinin A üyesi. |
| b | Dönüşüm matrisinin B üyesi. |
| c | Dönüşüm matrisinin C üyesi. |
| d | Dönüşüm matrisinin D üyesi. |
| e | Dönüşüm matrisinin E üyesi. |
| f | Dönüşüm matrisinin F üyesi. |
| elemanlar | Matrisin elemanları. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| rotation(alpha) | Verilen dönüş açı için matris oluşturur. |
| rotation(rotation) | Verilen dönüş açı için matris oluşturur. |
| transform(p) | Bu matrisi kullanarak noktayı dönüştürür. |
| transform(rect) | Dikdörtgeni dönüştürür.<br/>            Eğer açı 90 * N derece değilse sınırlayıcı dikdörtgen döndürülür. |
| skew(alpha, beta) | Verilen dönüş açı için matris oluşturur. |
| get_angle(rotation) | Dönüşümü açıya (derece) çevirir |
| multiply(other) | Matris'i diğer matris ile çarpar. |
| add(other) | Matris'i diğer matris'e ekler. |
| reverse() | Ters matrisi hesaplar. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

