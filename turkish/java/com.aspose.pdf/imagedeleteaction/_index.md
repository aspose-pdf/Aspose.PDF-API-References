---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Aspose.PDF for Java API Referansı"
description: "Görüntü nesnesi koleksiyondan kaldırıldığında görüntü nesnesiyle gerçekleştirilen eylem. Görüntü nesnesi kaldırıldığında"
type: docs
weight: 2290
url: /tr/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Görüntü nesnesi koleksiyondan kaldırıldığında görüntü nesnesiyle gerçekleştirilen eylem. Görüntü nesnesi kaldırıldığında

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Check](#Check) | Görüntü, koleksiyondan kaldırılacak ve görüntü nesnesi yalnızca diğer sayfalardan görüntüye başka referans yoksa kaldırılacaktır. Bu, ForceDelete seçeneğiyle karşılaştırıldığında daha fazla zaman alabilir. |
| [ForceDelete](#ForceDelete) | Görüntü, koleksiyondan kaldırılacak ve görüntü nesnesi belgeden kaldırılacaktır. Aynı nesne üzerinde başka referanslar varsa belge bozulabilir. |
| [KeepContents](#KeepContents) | Görüntü, koleksiyondan kaldırılacaktır. Sayfa içeriği görüntüye referanslar içeriyorsa bunlar kaldırılmayacaktır. Belge geçersiz hale gelebilir. |
| [None](#None) | Görüntü, koleksiyondan ve sayfa içeriğinden kaldırılacak, ancak görüntü nesnesi silinmeyecektir. Dosya boyutu azalmayacaktır. |

### Check {#Check}
```
public static final int Check
```

Görüntü, koleksiyondan kaldırılacak ve görüntü nesnesi yalnızca diğer sayfalardan görüntüye başka referans yoksa kaldırılacaktır. Bu, ForceDelete seçeneğiyle karşılaştırıldığında daha fazla zaman alabilir.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

Görüntü, koleksiyondan kaldırılacak ve görüntü nesnesi belgeden kaldırılacaktır. Aynı nesne üzerinde başka referanslar varsa belge bozulabilir.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

Görüntü, koleksiyondan kaldırılacaktır. Sayfa içeriği görüntüye referanslar içeriyorsa bunlar kaldırılmayacaktır. Belge geçersiz hale gelebilir.

### None {#None}
```
public static final int None
```

Görüntü, koleksiyondan ve sayfa içeriğinden kaldırılacak, ancak görüntü nesnesi silinmeyecektir. Dosya boyutu azalmayacaktır.
