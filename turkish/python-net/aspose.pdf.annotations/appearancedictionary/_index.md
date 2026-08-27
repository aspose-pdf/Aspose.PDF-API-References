---
title: "AppearanceDictionary"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sayfada ek açıklamanın görsel olarak nasıl sunulacağını belirten ek açıklama görünüm sözlüğü."
type: docs
weight: 60
url: /tr/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Sayfada ek açıklamanın görsel olarak nasıl sunulacağını belirten ek açıklama görünüm sözlüğü.

AppearanceDictionary türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_fixed_size | Sözlüğün sabit boyuta sahip olup olmadığını gösteren bir değeri alır. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | D).state değerleri,<br/>            burada N - normal görünüm, R - rollover görünüm, D - down görünüm ve state - durumun adı<br/>            (ör. On, Off onay kutuları için). |
| değerler | Sözlüğün değerlerinin listesini alır. <br/>            Sonuç koleksiyonu XForm nesnelerinin listesini içerir. |
| is_synchronized | Sözlüğe erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| sync_root | Sözlüğe erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| add(key, value) | Sağlanan anahtar ve değerle bir öğe ekler. |
| add(key, value) | Belirtilen anahtar için X form ekle. |
| copy_to(array, index) | Sözlüğün öğelerini belirli bir dizi indeksinden başlayarak bir Array'e kopyalar. |
| contains_key(key) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| remove(key) | Anahtarı sözlükten kaldırır. |
| try_get_value(key, value) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |

### Ayrıca Bakınız

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

