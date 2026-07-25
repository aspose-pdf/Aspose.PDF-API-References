---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة للمقارنة الرسومية لمستندات PDF. يجب استخدامها للبحث عن تغييرات صغيرة، خاصةً ذات الطبيعة الرسومية. لمقارنة تغييرات محتوى النص، استخدم فئة أخرى."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

يمثل فئة للمقارنة الرسومية بين مستندات PDF. يجب استخدامها للبحث عن تغييرات صغيرة، خاصةً ذات طبيعة رسومية. لمقارنة تغييرات محتوى النص، استخدم فئات مقارنة PDF أخرى.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | ينشئ مثيلاً لفئة {@link GraphicalPdfComparer}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | يقارن المستندات رسوميًا. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | يقارن المستندات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في صورة. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF. |
| [getColor](#getColor--) | يحصل على لون علم التغيير ويضبطه. اللون الافتراضي هو الأحمر. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | يحصل على الفروقات بين صور الصفحات. النتيجة تحتوي على صورة للصفحة الأولى التي تم مقارنتها ومصفوفة من الاختلافات. |
| [getResolution](#getResolution--) | يحصل على دقة الصور الناتجة ويضبطها. القيمة الافتراضية هي 150dpi. |
| [getThreshold](#getThreshold--) | يحصل على قيمة العتبة بالنسبة المئوية ويضبطها. تسمح لك هذه القيمة بتجاهل التغييرات الصغيرة إذا لم تكن ذات أهمية بالنسبة لك. القيمة الافتراضية هي 0%. |
| [setColor](#setColor-com.aspose.pdf.Color-) | يحصل على لون علم التغيير ويضبطه. اللون الافتراضي هو الأحمر. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | يحصل على دقة الصور الناتجة ويضبطها. القيمة الافتراضية هي 150dpi. |
| [setThreshold](#setThreshold-double-) | يحصل على قيمة العتبة بالنسبة المئوية ويضبطها. تسمح لك هذه القيمة بتجاهل التغييرات الصغيرة إذا لم تكن ذات أهمية بالنسبة لك. القيمة الافتراضية هي 0%. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

ينشئ مثيلاً لفئة {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
يقارن المستندات رسوميًا.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
يقارن المستندات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في صورة.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
يقارن الصفحات رسوميًا. يتم وضع نتيجة المقارنة في مستند PDF.

### getColor {#getColor--}
```
public final Color getColor()
```

يحصل على لون علم التغيير ويضبطه. اللون الافتراضي هو الأحمر.

**Returns:**
مثيل Color

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
يحصل على الفروقات بين صور الصفحات. النتيجة تحتوي على صورة للصفحة الأولى التي تم مقارنتها ومصفوفة من الاختلافات.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

يحصل على دقة الصور الناتجة ويضبطها. القيمة الافتراضية هي 150dpi.

**Returns:**
مثيل Resolution

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

يحصل على قيمة العتبة بالنسبة المئوية ويضبطها. تسمح لك هذه القيمة بتجاهل التغييرات الصغيرة إذا لم تكن ذات أهمية بالنسبة لك. القيمة الافتراضية هي 0%.

**Returns:**
قيمة double

### setColor {#setColor-com.aspose.pdf.Color-}
يحصل على لون علم التغيير ويضبطه. اللون الافتراضي هو الأحمر.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
يحصل على دقة الصور الناتجة ويضبطها. القيمة الافتراضية هي 150dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

يحصل على قيمة العتبة بالنسبة المئوية ويضبطها. تسمح لك هذه القيمة بتجاهل التغييرات الصغيرة إذا لم تكن ذات أهمية بالنسبة لك. القيمة الافتراضية هي 0%.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
