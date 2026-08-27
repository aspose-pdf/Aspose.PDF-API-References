---
title: "SubPath"
linktitle: "SubPath"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfadaki vektör grafik nesnesini temsil eder. Temelde, vektör grafik nesneleri iki SubPath grubuyla temsil edilir. Bunlardan biri bir dizi çizgiyle temsil edilir ve."
type: docs
weight: 60
url: /tr/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Sayfada vektör grafik nesnesini temsil eder. Temelde, vektör grafik nesneleri iki SubPath grubuyla temsil edilir. Bunlardan biri çizgi ve eğriler kümesiyle temsil edilir. Diğerleri ise dikdörtgenler olarak sunulur ve bazen karıştırılabilir. Genellikle renkli bir dikdörtgen alandır, ancak çok sık bu dikdörtgen sayfanın başına yerleştirilir ve sayfanın tüm alanını beyaz olarak tanımlar. Böylece SubPath elde edersiniz, ancak görsel olarak sadece sayfadaki metni görürsünüz.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRectangle](#getRectangle--) | GraphicElement'in sınırlayıcı dikdörtgenini alır. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

GraphicElement'in sınırlayıcı dikdörtgenini alır.

**Returns:**
Dikdörtgen örneği
