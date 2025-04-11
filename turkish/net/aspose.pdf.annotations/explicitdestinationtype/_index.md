---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ExplicitDestinationType enum. Açık hedef türlerini sıralar
type: docs
weight: 1690
url: /tr/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumerasyonu

Açık hedef türlerini sıralar.

```csharp
public enum ExplicitDestinationType
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| XYZ | `0` | Sayfayı, pencerenin sol üst köşesine yerleştirilmiş (sol, üst) koordinatları ile ve sayfanın içeriğini zoom faktörü ile büyütülmüş olarak görüntüler. Sol, üst veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. 0 zoom değeri, null değeri ile aynı anlama gelir. |
| Fit | `1` | Sayfayı, içeriği, pencere içinde yatay ve dikey olarak tamamen sığacak şekilde yeterince büyütülmüş olarak görüntüler. Gerekli yatay ve dikey büyütme faktörleri farklıysa, ikisinden daha küçük olanı kullanarak sayfayı diğer boyutta pencere içinde ortalar. |
| FitH | `2` | Sayfayı, dikey koordinat üstü pencerenin üst kenarına yerleştirilmiş ve sayfanın içeriği, sayfanın tam genişliğini pencere içinde sığacak şekilde yeterince büyütülmüş olarak görüntüler. Üst için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| FitV | `3` | Sayfayı, yatay koordinat solu pencerenin sol kenarına yerleştirilmiş ve sayfanın içeriği, sayfanın tam yüksekliğini pencere içinde sığacak şekilde yeterince büyütülmüş olarak görüntüler. Sol için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| FitR | `4` | Sayfayı, içeriği, sol, alt, sağ ve üst koordinatları ile belirtilen dikdörtgeni tamamen pencere içinde yatay ve dikey olarak sığacak şekilde yeterince büyütülmüş olarak görüntüler. Gerekli yatay ve dikey büyütme faktörleri farklıysa, ikisinden daha küçük olanı kullanarak dikdörtgeni diğer boyutta pencere içinde ortalar. Herhangi bir parametre için null değeri, öngörülemeyen davranışa neden olabilir. |
| FitB | `5` | Sayfayı, içeriği, sınır kutusunu tamamen pencere içinde yatay ve dikey olarak sığacak şekilde yeterince büyütülmüş olarak görüntüler. Gerekli yatay ve dikey büyütme faktörleri farklıysa, ikisinden daha küçük olanı kullanarak sınır kutusunu diğer boyutta pencere içinde ortalar. |
| FitBH | `6` | Sayfayı, dikey koordinat üstü pencerenin üst kenarına yerleştirilmiş ve sayfanın içeriği, sınır kutusunun tam genişliğini pencere içinde sığacak şekilde yeterince büyütülmüş olarak görüntüler. Üst için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |
| FitBV | `7` | Sayfayı, yatay koordinat solu pencerenin sol kenarına yerleştirilmiş ve sayfanın içeriği, sınır kutusunun tam yüksekliğini pencere içinde sığacak şekilde yeterince büyütülmüş olarak görüntüler. Sol için null değeri, o parametrenin mevcut değerinin değiştirilmeden korunacağını belirtir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)