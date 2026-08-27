---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الفئة الأساسية لكائن الرسومات على الصفحة."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

يمثل الفئة الأساسية لكائن الرسومات على الصفحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة يفضَّل استخدام Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | يطلق جميع الموارد المستخدمة من قبل الفئة {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | يحصل على مصفوفة العنصر الرسومي. يتم تعيين المصفوفة عند إنشاء العنصر. تتغير عندما يتم استدعاء SetPosition(). |
| [getOperators](#getOperators--) | يحصل على مجموعة من المشغلات التي تمثل العنصر. |
| [getParent](#getParent--) | يحصل على {@link XFormPlacement} الحالي الذي يقع فيه العنصر. |
| [getPosition](#getPosition--) | يحصل أو يضبط الموضع في مساحة الإحداثيات الحالية. إذا كان Parent #getParent/#setParent(XFormPlacement) غير فارغ (null) فإن للعنصر مساحة إحداثيات xForm. |
| [getRectangle](#getRectangle--) | يحصل على المستطيل المحيط بـ {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | يحصل على الصفحة التي تم استخراج العنصر الرسومي منها. |
| [remove](#remove--) | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر لإزالتها من الأفضل استخدام Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | يحوّل العنصر إلى صورة SVG واحدة. |
| [saveToSvg](#saveToSvg-java.lang.String-) | يحوّل العنصر إلى صورة SVG واحدة. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | يحصل أو يضبط الموضع في مساحة الإحداثيات الحالية. إذا كان Parent #getParent/#setParent(XFormPlacement) غير فارغ (null) فإن للعنصر مساحة إحداثيات xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة يفضَّل استخدام Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

يطلق جميع الموارد المستخدمة من قبل الفئة {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

يحصل على مصفوفة العنصر الرسومي. يتم تعيين المصفوفة عند إنشاء العنصر. تتغير عندما يتم استدعاء SetPosition().

**Returns:**
مثيل المصفوفة

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

يحصل على مجموعة من المشغلات التي تمثل العنصر.

**Returns:**
قائمة مثيلات المشغل

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

يحصل على {@link XFormPlacement} الحالي الذي يقع فيه العنصر.

**Returns:**
مثيل XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

يحصل أو يضبط الموضع في مساحة الإحداثيات الحالية. إذا كان Parent #getParent/#setParent(XFormPlacement) غير فارغ (null) فإن للعنصر مساحة إحداثيات xForm.

**Returns:**
مثيل Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

يحصل على المستطيل المحيط بـ {@link GraphicElement}.

**Returns:**
مثيل Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

يحصل على الصفحة التي تم استخراج العنصر الرسومي منها.

**Returns:**
كائن الصفحة

### remove {#remove--}
```
public final void remove()
```

يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر لإزالتها من الأفضل استخدام Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

يحوّل العنصر إلى صورة SVG واحدة.

**Returns:**
سلسلة SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
يحوّل العنصر إلى صورة SVG واحدة.

**Returns:**
سلسلة SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
يحصل أو يضبط الموضع في مساحة الإحداثيات الحالية. إذا كان Parent #getParent/#setParent(XFormPlacement) غير فارغ (null) فإن للعنصر مساحة إحداثيات xForm.
