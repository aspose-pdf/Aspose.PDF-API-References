---
title: "XForm"
linktitle: "XForm"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل XForm"
type: docs
weight: 5590
url: /ar/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

الفئة تمثل XForm

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | يفرغ الذاكرة |
| [containsOwnResources](#containsOwnResources--) | يرجع True إذا كان يحتوي على الموارد الخاصة |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | ينشئ XForm جديدًا في المستند. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | ينشئ XForm يكرر محتويات الصفحة. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | يفرغ الذاكرة |
| [freeMemory](#freeMemory--) | يمسح البيانات المخزنة مؤقتًا |
| [getBBox](#getBBox--) | يحصل على صندوق الحدود للنموذج. |
| [getContents](#getContents--) | يحصل على عوامل النموذج. |
| [getEngineObj](#getEngineObj--) | داخلي فقط |
| [getIT](#getIT--) | يحصل على IT للنموذج. IT النموذج هو اسم يصف هدف XObject. |
| [getMatrix](#getMatrix--) | يحصل على مصفوفة النموذج. |
| [getName](#getName--) | يحصل على اسم النموذج. اسم النموذج هو الاسم المستخدم للإشارة إلى النموذج في قاموس XObejct في موارد الصفحة. |
| [getOpi](#getOpi--) | يحصل على واجهة ما قبل الطباعة المفتوحة (OPI). |
| [getRectangle](#getRectangle--) | يحصل على مستطيل النموذج. |
| [getResources](#getResources--) | يعيد موارد Form X-Object. إذا لم يكن لدى For موارد وكان allowCreate صحيحًا، سيتم إنشاء الموارد تلقائيًا للنموذج. |
| [getResources](#getResources-boolean-) | يعيد موارد Form X-Object |
| [getResourcesField](#getResourcesField--) | يحصل على موارد Form XObject. |
| [getSubtype](#getSubtype--) | يحصل على النوع الفرعي للنموذج. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | يضبط صندوق حدود النموذج. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | يضبط مصفوفة النموذج. |
| [setName](#setName-java.lang.String-) | يضبط اسم النموذج. اسم النموذج هو الاسم المستخدم للإشارة إلى النموذج في قاموس XObejct في موارد الصفحة. |

### close {#close--}
```
public final void close()
```

يفرغ الذاكرة

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

يرجع True إذا كان يحتوي على الموارد الخاصة

**Returns:**
قيمة منطقية

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
ينشئ XForm جديدًا في المستند.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
ينشئ XForm يكرر محتويات الصفحة.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

يفرغ الذاكرة

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

يمسح البيانات المخزنة مؤقتًا

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

يحصل على صندوق الحدود للنموذج.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

يحصل على عوامل النموذج.

**Returns:**
كائن OperatorCollection

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

داخلي فقط

**Returns:**
كائن IPdfObject

### getIT {#getIT--}
```
public final String getIT()
```

يحصل على IT للنموذج. IT النموذج هو اسم يصف هدف XObject.

**Returns:**
قيمة سلسلة

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

يحصل على مصفوفة النموذج.

**Returns:**
مصفوفة

### getName {#getName--}
```
public String getName()
```

يحصل على اسم النموذج. اسم النموذج هو الاسم المستخدم للإشارة إلى النموذج في قاموس XObejct في موارد الصفحة.

**Returns:**
سلسلة

### getOpi {#getOpi--}
```
public Opi getOpi()
```

يحصل على واجهة ما قبل الطباعة المفتوحة (OPI).

**Returns:**
مثيل Opi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على مستطيل النموذج.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

يعيد موارد Form X-Object. إذا لم يكن لدى For موارد وكان allowCreate صحيحًا، سيتم إنشاء الموارد تلقائيًا للنموذج.

**Returns:**
مثيل Resources

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

يعيد موارد Form X-Object

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| allowCreate |  | إذا لم يكن لدى For موارد وكان allowCreate صحيحًا، سيتم إنشاء الموارد تلقائيًا للنموذج. |

**Returns:**
مثيل Resources

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

يحصل على موارد Form XObject.

**Returns:**
مثيل Resources. إذا لم يكن لدى For موارد، سيتم إنشاء الموارد تلقائيًا للنموذج.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

يحصل على النوع الفرعي للنموذج.

**Returns:**
قيمة سلسلة

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
يضبط صندوق حدود النموذج.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
يضبط مصفوفة النموذج.

### setName {#setName-java.lang.String-}
يضبط اسم النموذج. اسم النموذج هو الاسم المستخدم للإشارة إلى النموذج في قاموس XObejct في موارد الصفحة.
