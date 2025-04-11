---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationFlags enum. Notun çeşitli özelliklerini belirten bir dizi bayrak
type: docs
weight: 1440
url: /tr/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumerasyonu

Notun çeşitli özelliklerini belirten bir dizi bayrak.

```csharp
[Flags]
public enum AnnotationFlags
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Varsayılan | `0` | Varsayılan değer. |
| Görünmez | `1` | Ayarlandığında, not standart not türlerinden birine ait değilse ve hiçbir not işleyici mevcut değilse notu görüntüleme. Temizse, böyle bir bilinmeyen notu, varsa görünüm sözlüğü tarafından belirtilen bir görünüm akışı kullanarak görüntüle. |
| Gizli | `2` | Ayarlandığında, notu görüntüleme veya yazdırma veya kullanıcının etkileşimde bulunmasına izin verme, not türüne veya bir not işleyicisinin mevcut olup olmadığına bakılmaksızın. Ekran alanı sınırlı olduğunda, notları seçici olarak gizleme ve gösterme yeteneği, çevrimiçi yardım sistemlerine benzer işlevsellikte yardımcı açılır bilgileri görüntülemek için görünüm akışları ile birleştirilebilir. |
| Yazdır | `4` | Ayarlandığında, sayfa yazdırıldığında notu yazdır. Temizse, not ekran üzerinde görüntülense bile asla yazdırma. Bu, örneğin, yazdırılmış sayfada anlamlı bir amaç taşımayan etkileşimli butonları temsil eden notlar için yararlı olabilir. |
| Yakınlaştırma Yok | `8` | Ayarlandığında, notun görünümünü sayfanın büyütmesiyle eşleşecek şekilde ölçeklendirme. Notun sayfadaki yeri (not dikdörtgeninin sol üst köşesi tarafından tanımlanır) sabit kalır, sayfa büyütmesine bakılmaksızın. |
| Döndürme Yok | `10` | Ayarlandığında, notun görünümünü sayfanın döndürmesine eşleşecek şekilde döndürme. Not dikdörtgeninin sol üst köşesi, sayfa döndürmesine bakılmaksızın sayfada sabit bir konumda kalır. |
| Görünüm Yok | `20` | Ayarlandığında, notu ekranda görüntüleme veya kullanıcının etkileşimde bulunmasına izin verme. Not yazdırılabilir (Yazdır bayrağının ayarına bağlı olarak) ancak ekran görüntüleme ve kullanıcı etkileşimi açısından gizli olarak kabul edilmelidir. |
| Sadece Okunur | `40` | Ayarlandığında, notun kullanıcı ile etkileşimde bulunmasına izin verme. Not görüntülenebilir veya yazdırılabilir (Görünüm Yok ve Yazdır bayraklarının ayarlarına bağlı olarak) ancak fare tıklamalarına yanıt vermemeli veya fare hareketlerine yanıt olarak görünümünü değiştirmemelidir. Bu bayrak, widget notları için göz ardı edilir; işlevi, ilişkili form alanının Sadece Okunur bayrağı tarafından kapsanır. |
| Kilitli | `80` | Ayarlandığında, notun silinmesine veya özelliklerinin (konum ve boyut dahil) kullanıcı tarafından değiştirilmesine izin verme. Ancak, bu bayrak, bir form alanının değeri gibi notun içeriğinde değişiklikleri kısıtlamaz. |
| Görünüm Yok Değiştir | `100` | Ayarlandığında, belirli olaylar için Görünüm Yok bayrağının yorumunu tersine çevir. Tipik bir kullanım, üzerine fare imleci tutulduğunda yalnızca görünen bir not olmaktır. |
| Kilitli İçerikler | `200` | Ayarlandığında, notun içeriğinin kullanıcı tarafından değiştirilmesine izin verme. Bu bayrak, notun silinmesini veya diğer not özelliklerinde (konum ve boyut gibi) değişiklikleri kısıtlamaz. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)