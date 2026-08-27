---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة PDF3DAnnotation. لا يمكن وراثة هذه الفئة. @see Annotation"
type: docs
weight: 3560
url: /ar/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

فئة PDF3DAnnotation. لا يمكن وراثة هذه الفئة. @see Annotation

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | يُنشئ مثالًا جديدًا من الفئة {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | يُنشئ مثالًا جديدًا من الفئة {@code PDF3DAnnotation}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل الزائر لمعالجة التعليقات التوضيحية. |
| [clearImagePreview](#clearImagePreview--) | يمسح معاينة الصورة. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق. القيمة: نوع التعليق. |
| [getContent](#getContent--) | يحصل أو يضبط المحتوى. القيمة: المحتوى. |
| [getImagePreview](#getImagePreview--) | يحصل على معاينة الصورة. |
| [getLightingScheme](#getLightingScheme--) | يحصل على مخطط الإضاءة. القيمة: مخطط الإضاءة. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | يحصل على العمل الفني ثلاثي الأبعاد. القيمة: عمل PDF3 d الفني. |
| [getRenderMode](#getRenderMode--) | يحصل على وضع العرض. القيمة: وضع العرض. |
| [getViewArray](#getViewArray--) | يحصل على مصفوفة العرض. القيمة: مصفوفة العرض. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | يحصل أو يضبط المحتوى. القيمة: المحتوى. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | يضبط فهرس العرض الافتراضي. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | يضبط معاينة الصورة. |
| [setImagePreview](#setImagePreview-java.lang.String-) | يضبط معاينة الصورة. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
يُنشئ مثالًا جديدًا من الفئة {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
يُنشئ مثالًا جديدًا من الفئة {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل الزائر لمعالجة التعليقات التوضيحية.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

يمسح معاينة الصورة.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق. القيمة: نوع التعليق.

**Returns:**
قيمة int

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

يحصل أو يضبط المحتوى. القيمة: المحتوى.

**Returns:**
PDF3DContent object

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

يحصل على معاينة الصورة.

**Returns:**
معاينة الصورة كتيار.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

يحصل على مخطط الإضاءة. القيمة: مخطط الإضاءة.

**Returns:**
PDF3DLightingScheme object

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

يحصل على العمل الفني ثلاثي الأبعاد. القيمة: عمل PDF3 d الفني.

**Returns:**
كائن PDF3DArtwork

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

يحصل على وضع العرض. القيمة: وضع العرض.

**Returns:**
كائن PDF3DRenderMode

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

يحصل على مصفوفة العرض. القيمة: مصفوفة العرض.

**Returns:**
كائن PDF3DViewArray

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
يحصل أو يضبط المحتوى. القيمة: المحتوى.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

يضبط فهرس العرض الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس العرض الافتراضي. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
يضبط معاينة الصورة.

### setImagePreview {#setImagePreview-java.lang.String-}
يضبط معاينة الصورة.
