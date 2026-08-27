---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل كائن ماص لعناصر الرسومات. يقوم بإجراء بحث عن الرسومات ويوفر الوصول إلى نتائج البحث عبر {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /ar/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

يمثل كائن ماص لعناصر الرسومات. يقوم ببحث الرسومات ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [dispose](#dispose--) | يطلق جميع الموارد المستخدمة من قبل الفئة {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | يحصل على مجموعة من حالات البحث التي يتم تقديمها باستخدام كائنات {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | استئناف التحديث لـ forPage#getContents وجميع @link XForm#getContents تم ذلك لزيادة الأداء، انظر أيضًا. |
| [suppressUpdate](#suppressUpdate--) | يقمع التحديث لـ Page#getContents وجميع @link XForm#getContents تم ذلك لزيادة الأداء، انظر أيضًا. |
| [visit](#visit-com.aspose.pdf.Page-) | ينفذ البحث على الصفحة المحددة. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

يطلق جميع الموارد المستخدمة من قبل الفئة {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

يحصل على مجموعة من حالات البحث التي يتم تقديمها باستخدام كائنات {@link GraphicElement}.

**Returns:**
مثيل GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

استئناف التحديث لـ forPage#getContents وجميع @link XForm#getContents تم ذلك لزيادة الأداء، انظر أيضًا.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

يقمع التحديث لـ Page#getContents وجميع @link XForm#getContents تم ذلك لزيادة الأداء، انظر أيضًا.

### visit {#visit-com.aspose.pdf.Page-}
ينفذ البحث على الصفحة المحددة.
