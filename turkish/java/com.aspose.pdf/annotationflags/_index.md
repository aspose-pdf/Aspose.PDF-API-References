---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bayraklar Açıklamanın çeşitli özelliklerini belirten bir dizi ikili bayrak."
type: docs
weight: 90
url: /tr/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Bayraklar Açıklamanın çeşitli özelliklerini belirten bir dizi ikili bayrak.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Default](#Default) | Varsayılan değer. |
| [Hidden](#Hidden) | Eğer ayarlanırsa, ek açıklama türüne veya bir ek açıklama işleyicisinin mevcut olup olmamasına bakılmaksızın, ek açıklamayı görüntülemez veya yazdırmaz ve kullanıcının etkileşimine izin vermez. Ekran alanının sınırlı olduğu durumlarda, ek açıklamaları seçici olarak gizleme ve gösterme yeteneği, görünüm akımlarıyla birleştirilerek çevrimiçi yardım sistemlerine benzer işlevde yardımcı açılır bilgi görüntülemek için kullanılabilir. |
| [Invisible](#Invisible) | Eğer ayarlanırsa, standart ek açıklama türlerinden birine ait değilse ve bir ek açıklama işleyicisi yoksa ek açıklamayı görüntülemez. Eğer temizlenirse, varsa görünüm sözlüğü tarafından belirtilen bir görünüm akışı kullanarak bu bilinmeyen ek açıklamayı görüntüler. |
| [Locked](#Locked) | Ayarlanırsa, ek açıklamanın silinmesine veya özelliklerinin (konum ve boyut dahil) kullanıcı tarafından değiştirilmesine izin verilmez. Ancak, bu bayrak ek açıklamanın içeriğinde, örneğin bir form alanının değerinde yapılan değişiklikleri kısıtlamaz. |
| [LockedContents](#LockedContents) | Ayarlanırsa, ek açıklamanın içeriğinin kullanıcı tarafından değiştirilmesine izin verilmez. Bu bayrak, ek açıklamanın silinmesini veya konum ve boyut gibi diğer ek açıklama özelliklerinde yapılan değişiklikleri kısıtlamaz. |
| [NoRotate](#NoRotate) | Ayarlanırsa, ek açıklamanın görünümü sayfanın dönüşüne uyacak şekilde döndürülmez. Ek açıklama dikdörtgeninin sol üst köşesi, sayfa dönüşünden bağımsız olarak sayfada sabit bir konumda kalır. |
| [NoView](#NoView) | Ayarlanırsa, ek açıklama ekranda görüntülenmez ve kullanıcıyla etkileşime girmesine izin verilmez. Ek açıklama (Print bayrağının ayarına bağlı olarak) yazdırılabilir, ancak ekran görüntüsü ve kullanıcı etkileşimi açısından gizli kabul edilmelidir. |
| [NoZoom](#NoZoom) | Ayarlanırsa, ek açıklamanın görünümü sayfanın büyütme oranına uyacak şekilde ölçeklendirilmez. Ek açıklamanın sayfadaki konumu (ek açıklama dikdörtgeninin sol üst köşesiyle tanımlanır) sayfa büyütmesinden bağımsız olarak sabit kalır. |
| [Print](#Print) | Ayarlanırsa, sayfa yazdırıldığında ek açıklama da yazdırılır. Temizlenirse, ek açıklama ekran üzerinde görüntülense bile asla yazdırılmaz. Bu, örneğin etkileşimli itme düğmelerini temsil eden ek açıklamalar için yararlı olabilir; çünkü bu düğmeler yazdırılmış sayfada anlamlı bir amaç taşımaz. |
| [ReadOnly](#ReadOnly) | Ayarlanırsa, ek açıklamanın kullanıcıyla etkileşime girmesine izin verilmez. Ek açıklama (NoView ve Print bayraklarının ayarına bağlı olarak) görüntülenebilir veya yazdırılabilir, ancak fare tıklamalarına yanıt vermemeli ve fare hareketlerine göre görünümünü değiştirmemelidir. Bu bayrak widget ek açıklamaları için yok sayılır; işlevi ilgili form alanının ReadOnly bayrağı tarafından kapsanır. |
| [ToggleNoView](#ToggleNoView) | Ayarlanırsa, NoView bayrağının belirli olaylar için yorumlanması tersine çevrilir. Tipik bir kullanım, yalnızca fare imlecinin üzerine tutulduğunda görünen bir ek açıklamadır. |

### Default {#Default}
```
public static final int Default
```

Varsayılan değer.

### Hidden {#Hidden}
```
public static final int Hidden
```

Eğer ayarlanırsa, ek açıklama türüne veya bir ek açıklama işleyicisinin mevcut olup olmamasına bakılmaksızın, ek açıklamayı görüntülemez veya yazdırmaz ve kullanıcının etkileşimine izin vermez. Ekran alanının sınırlı olduğu durumlarda, ek açıklamaları seçici olarak gizleme ve gösterme yeteneği, görünüm akımlarıyla birleştirilerek çevrimiçi yardım sistemlerine benzer işlevde yardımcı açılır bilgi görüntülemek için kullanılabilir.

### Invisible {#Invisible}
```
public static final int Invisible
```

Eğer ayarlanırsa, standart ek açıklama türlerinden birine ait değilse ve bir ek açıklama işleyicisi yoksa ek açıklamayı görüntülemez. Eğer temizlenirse, varsa görünüm sözlüğü tarafından belirtilen bir görünüm akışı kullanarak bu bilinmeyen ek açıklamayı görüntüler.

### Locked {#Locked}
```
public static final int Locked
```

Ayarlanırsa, ek açıklamanın silinmesine veya özelliklerinin (konum ve boyut dahil) kullanıcı tarafından değiştirilmesine izin verilmez. Ancak, bu bayrak ek açıklamanın içeriğinde, örneğin bir form alanının değerinde yapılan değişiklikleri kısıtlamaz.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Ayarlanırsa, ek açıklamanın içeriğinin kullanıcı tarafından değiştirilmesine izin verilmez. Bu bayrak, ek açıklamanın silinmesini veya konum ve boyut gibi diğer ek açıklama özelliklerinde yapılan değişiklikleri kısıtlamaz.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Ayarlanırsa, ek açıklamanın görünümü sayfanın dönüşüne uyacak şekilde döndürülmez. Ek açıklama dikdörtgeninin sol üst köşesi, sayfa dönüşünden bağımsız olarak sayfada sabit bir konumda kalır.

### NoView {#NoView}
```
public static final int NoView
```

Ayarlanırsa, ek açıklama ekranda görüntülenmez ve kullanıcıyla etkileşime girmesine izin verilmez. Ek açıklama (Print bayrağının ayarına bağlı olarak) yazdırılabilir, ancak ekran görüntüsü ve kullanıcı etkileşimi açısından gizli kabul edilmelidir.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Ayarlanırsa, ek açıklamanın görünümü sayfanın büyütme oranına uyacak şekilde ölçeklendirilmez. Ek açıklamanın sayfadaki konumu (ek açıklama dikdörtgeninin sol üst köşesiyle tanımlanır) sayfa büyütmesinden bağımsız olarak sabit kalır.

### Print {#Print}
```
public static final int Print
```

Ayarlanırsa, sayfa yazdırıldığında ek açıklama da yazdırılır. Temizlenirse, ek açıklama ekran üzerinde görüntülense bile asla yazdırılmaz. Bu, örneğin etkileşimli itme düğmelerini temsil eden ek açıklamalar için yararlı olabilir; çünkü bu düğmeler yazdırılmış sayfada anlamlı bir amaç taşımaz.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Ayarlanırsa, ek açıklamanın kullanıcıyla etkileşime girmesine izin verilmez. Ek açıklama (NoView ve Print bayraklarının ayarına bağlı olarak) görüntülenebilir veya yazdırılabilir, ancak fare tıklamalarına yanıt vermemeli ve fare hareketlerine göre görünümünü değiştirmemelidir. Bu bayrak widget ek açıklamaları için yok sayılır; işlevi ilgili form alanının ReadOnly bayrağı tarafından kapsanır.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Ayarlanırsa, NoView bayrağının belirli olaylar için yorumlanması tersine çevrilir. Tipik bir kullanım, yalnızca fare imlecinin üzerine tutulduğunda görünen bir ek açıklamadır.
