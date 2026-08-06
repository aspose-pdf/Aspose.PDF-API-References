---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sol, üst koordinatları (left, top) pencerenin sol üst köşesine yerleştirilmiş ve sayfa içeriği zoom faktörüyle büyütülmüş açık bir hedefi temsil eder. left, top veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. Zoom değeri 0 ise aynı anlamı taşır, yani null değer gibidir."
type: docs
weight: 880
url: /tr/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Sol, üst koordinatları (left, top) pencerenin sol üst köşesine yerleştirilmiş ve sayfa içeriği zoom faktörüyle büyütülmüş açık bir hedefi temsil eder. left, top veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. Zoom değeri 0 ise aynı anlamı taşır, yani null değer gibidir.

XYZExplicitDestination türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | XYZExplicitDestination sınıfının yeni bir örneğini başlatır |
| XYZExplicitDestination(document, page_number, left, top, zoom) | XYZExplicitDestination sınıfının yeni bir örneğini başlatır |
| XYZExplicitDestination(page_number, left, top, zoom) | XYZExplicitDestination sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| sayfa | Hedef sayfa nesnesini alır |
| page_number | Hedef sayfa numarasını alır |
| left | Pencerenin sol üst köşesinin sol yatay koordinatını alır. |
| top | Pencerenin sol üst köşesinin üst dikey koordinatını alır. |
| zoom | Yakınlaştırma faktörünü alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Gerekirse sayfa dönüşünü dikkate alarak sayfanın belirtilen konumuna hedef oluştur. |
| create_destination(page, type, values) | ExplicitDestination türevi sınıfların örneklerini oluşturur. |
| create_destination(doc, page_number, type, values) | ExplicitDestination türevi sınıfların örneklerini oluşturur. |
| create_destination(page_number, type, values) | ExplicitDestination türevi sınıfların örneklerini oluşturur. |
| create_destination_to_upper_left_corner(page, zoom) | Belirtilen sayfanın sol üst köşesine hedef oluştur. |
| create_destination_to_upper_left_corner(page) | Belirtilen sayfanın sol üst köşesine hedef oluştur. |
| to_string() | Nesne durumunu string değerine dönüştürür. Örnek: "1 XYZ 100 200 3". |

### Ayrıca Bakınız

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

