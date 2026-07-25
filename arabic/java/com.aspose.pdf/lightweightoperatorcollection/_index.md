---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "مجموعة مشغّلات خفيفة الوزن. يُقصد استخدامها في السيناريوهات التي لا يكون فيها تدفق المحتوى الأساسي مرفقًا، حيث يُطلب فقط مجموعة المشغّلات كنتيجة."
type: docs
weight: 2700
url: /ar/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

مجموعة مشغّلات خفيفة الوزن. يُقصد استخدامها في السيناريوهات التي لا يكون فيها تدفق المحتوى الأساسي مرفقًا، حيث يُطلب فقط مجموعة المشغّلات كنتيجة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | تهيئة الكائن |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | تهيئة الكائن |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | تهيئة الكائن |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | إضافة عامل |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | إضافة LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا ينبغي أن يسبب التغيير تحديث المحتوى. |
| [clear](#clear--) | يمسح المجموعة. |
| [contains](#contains-com.aspose.pdf.Operator-) | تحقق مما إذا كان العنصر موجودًا في المجموعة. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | حذف داخلي Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> يحصل على المشغل حسب فهرسه. </p> <hr> <pre> يوضح المثال كيفية الحصول على مشغل محتويات الصفحة حسب الفهرس. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | للاستخدام الداخلي مشغل getUnrestricted |
| [insert](#insert-int-com.aspose.pdf.Operator-) | إدراج المشغل |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [iterator](#iterator--) | إرجاع المتكرر |
| [remove](#remove-com.aspose.pdf.Operator-) | يزيل المشغل من المجموعة. |
| [resumeUpdate](#resumeUpdate--) | يستأنف تحديث المستند. يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | يضبط المشغل حسب فهرسه. <hr> <pre> يوضح المثال كيفية الحصول على مشغل محتويات الصفحة حسب الفهرس. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | عدد المشغلات |
| [suppressUpdate](#suppressUpdate--) | يقمع تحديث بيانات المحتوى. لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate. |
| [toList](#toList--) | يعيد قائمة المشغلات. |
| [updateData](#updateData--) | داخلي |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

تهيئة الكائن

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
تهيئة الكائن

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
تهيئة الكائن

### add {#add-com.aspose.pdf.Operator-}
إضافة عامل

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
إضافة LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا ينبغي أن يسبب التغيير تحديث المحتوى.

### clear {#clear--}
```
public void clear()
```

يمسح المجموعة.

### contains {#contains-com.aspose.pdf.Operator-}
تحقق مما إذا كان العنصر موجودًا في المجموعة.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

حذف داخلي Unrestrictedelement

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة int |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> يحصل على المشغل حسب فهرسه. </p> <hr> <pre> يوضح المثال كيفية الحصول على مشغل محتويات الصفحة حسب الفهرس. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس المشغل. يبدأ الترقيم من 1. |

**Returns:**
المشغل من الفهرس المطلوب

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

للاستخدام الداخلي مشغل getUnrestricted

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة int |

**Returns:**
كائن المشغل

### insert {#insert-int-com.aspose.pdf.Operator-}
إدراج المشغل

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

إرجاع المتكرر

**Returns:**
{@code IGenericEnumerator<Operator>} كائن

### remove {#remove-com.aspose.pdf.Operator-}
يزيل المشغل من المجموعة.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

يستأنف تحديث المستند. يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
يضبط المشغل حسب فهرسه. <hr> <pre> يوضح المثال كيفية الحصول على مشغل محتويات الصفحة حسب الفهرس. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

عدد المشغلات

**Returns:**
قيمة int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

يقمع تحديث بيانات المحتوى. لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

يعيد قائمة المشغلات.

**Returns:**
قائمة المشغلات.

### updateData {#updateData--}
```
public void updateData()
```

داخلي
