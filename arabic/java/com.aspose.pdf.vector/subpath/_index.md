---
title: "SubPath"
linktitle: "SubPath"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل كائن الرسومات المتجهة على الصفحة. أساسًا، يتم تمثيل كائنات الرسومات المتجهة بمجموعتين من SubPaths. واحدة منها تمثل بمجموعة من الخطوط و."
type: docs
weight: 60
url: /ar/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

يمثل كائن رسومات متجهة على الصفحة. أساسًا، يتم تمثيل كائنات الرسومات المتجهة بمجموعتين من SubPaths. يتم تمثيل إحداهما بمجموعة من الخطوط والمنحنيات. تُعرض الأخرى ك rectangles وقد يحدث ارتباك أحيانًا. عادةً ما تكون مساحة مستطيلة لها لون، لكن كثيرًا ما يتم وضع هذا المستطيل في بداية الصفحة ويحدد كامل مساحة الصفحة باللون الأبيض. لذا تحصل على SubPath، لكن بصريًا لا ترى سوى النص على الصفحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRectangle](#getRectangle--) | يحصل على المستطيل المحيط بـ GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على المستطيل المحيط بـ GraphicElement.

**Returns:**
مثيل Rectangle
