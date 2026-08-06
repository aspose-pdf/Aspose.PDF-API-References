---
title: "AnnotationFlags"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Ek açıklamanın çeşitli özelliklerini belirten bayrakların bir kümesi."
type: docs
weight: 930
url: /tr/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Ek açıklamanın çeşitli özelliklerini belirten bayrakların bir kümesi.

## Members
| Üye adı | Açıklama |
| :- | :- |
| DEFAULT | Varsayılan değer. |
| INVISIBLE | Ayarlanırsa, standart açıklama türlerinden birine ait değilse ve hiçbir açıklama işleyicisi mevcut değilse açıklamayı gösterme.<br/>            Ayarlama kaldırılırsa, böyle bir bilinmeyen açıklamayı, varsa açıklama sözlüğü tarafından belirtilen bir görünüm akışı kullanarak göster. |
| HIDDEN | Ayarlanırsa, açıklamayı gösterme veya yazdırma ve kullanıcıyla etkileşime girmesine izin verme,<br/>            açıklama türüne veya bir açıklama işleyicisinin mevcut olup olmadığına bakılmaksızın.<br/>            Ekran alanının sınırlı olduğu durumlarda, açıklamaları seçici olarak gizleme ve gösterme yeteneği,<br/>            görünüm akışlarıyla birleştirilerek çevrimiçi yardım sistemlerine benzer işlevde ek bilgi pencereleri görüntülemek için kullanılabilir. |
| YAZDIR | Ayarlanırsa, sayfa yazdırıldığında açıklamayı da yazdır. Ayarlama kaldırılırsa, açıklamayı asla yazdırma,<br/>            ekran üzerinde gösterilip gösterilmediğine bakılmaksızın. Bu, örneğin, etkileşimli itme düğmelerini temsil eden açıklamalar için faydalı olabilir; bu tür açıklamalar basılı sayfada anlamlı bir amaç taşımaz. |
| NO_ZOOM | Ayarlanırsa, açıklamanın görünümünü sayfanın büyütmesiyle eşleşecek şekilde ölçeklendirme.<br/>            Açıklamanın sayfadaki konumu (açıklama dikdörtgeninin sol üst köşesiyle tanımlanır)<br/>            sayfa büyütmesine bakılmaksızın sabit kalır. |
| NO_ROTATE | Ayarlanırsa, açıklamanın görünümünü sayfanın dönüşüyle eşleşecek şekilde döndürme.<br/>            Açıklama dikdörtgeninin sol üst köşesi sayfada sabit bir konumda kalır,<br/>            sayfa dönüşüne bakılmaksızın. |
| NO_VIEW | Ayarlanırsa, açıklamayı ekranda gösterme ve kullanıcıyla etkileşime girmesine izin verme.<br/>            Açıklama (Print bayrağının ayarına bağlı olarak) yazdırılabilir<br/>            ancak ekran görüntüsü ve kullanıcı etkileşimi açısından gizli kabul edilmelidir. |
| READ_ONLY | Ayarlanırsa, açıklamanın kullanıcıyla etkileşime girmesine izin verme. Açıklama gösterilebilir<br/>            veya yazdırılabilir (NoView ve Print bayraklarının ayarına bağlı olarak) ancak fare tıklamalarına yanıt vermemeli<br/>            veya fare hareketlerine karşı görünümünü değiştirmemelidir. Bu bayrak widget açıklamaları için yok sayılır;<br/>            işlevi ilgili form alanının ReadOnly bayrağı tarafından kapsanır. |
| LOCKED | Ayarlanırsa, açıklamanın silinmesine veya özelliklerinin (konum ve boyut dahil) kullanıcı tarafından değiştirilmesine izin verme.<br/>            Ancak bu bayrak, açıklamanın içeriğindeki değişiklikleri kısıtlamaz,<br/>            örneğin bir form alanının değerini. |
| TOGGLE_NO_VIEW | Ayarlanırsa, NoView bayrağının belirli olaylar için yorumunu tersine çevirir.<br/>            Tipik bir kullanım, fare imlecinin üzerine tutulduğunda yalnızca görünen bir ek açıklama sağlamaktır. |
| LOCKED_CONTENTS | Ayarlanırsa, ek açıklamanın içeriğinin kullanıcı tarafından değiştirilmesine izin verilmez.<br/>            Bu bayrak, ek açıklamanın silinmesini veya konum ve boyut gibi diğer ek açıklama özelliklerinde yapılan değişiklikleri kısıtlamaz,<br/>            örneğin konum ve boyut. |

### Ayrıca Bakınız

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

