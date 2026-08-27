---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل موضع XForm. إذا تم عرض XForm على الصفحة أكثر من مرة واحدة، فإن جميع XformPlacements المرتبطة بهذا XForm ستشارك عناصر رسومية مشتركة، ولكن."
type: docs
weight: 70
url: /ar/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

يمثل موضع XForm. إذا تم عرض XForm على الصفحة أكثر من مرة واحدة، فإن جميع XformPlacements المرتبطة بهذا XForm ستشارك عناصر رسومية مشتركة، لكن بحالات رسومية مختلفة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة يفضَّل استخدام Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | يحصل على العناصر الرسومية داخل هذا XForm. |
| [getName](#getName--) | يحصل على اسم الـ XForm. |
| [getRectangle](#getRectangle--) | يحصل على المستطيل المحيط بـ GraphicElement. |
| [getXForm](#getXForm--) | يحصل على XForm المرتبط بهذا XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | يحصل أو يعيّن الموضع في مساحة الإحداثيات الحالية. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة يفضَّل استخدام Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

يحصل على العناصر الرسومية داخل هذا XForm.

**Returns:**
مثيل GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

يحصل على اسم الـ XForm.

**Returns:**
قيمة سلسلة

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على المستطيل المحيط بـ GraphicElement.

**Returns:**
مثيل Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

يحصل على XForm المرتبط بهذا XFormPlacement.

**Returns:**
مثيل XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
يحصل أو يعيّن الموضع في مساحة الإحداثيات الحالية.
