---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل مجموعة من المشغلات"
type: docs
weight: 3190
url: /ar/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

الفئة تمثل مجموعة من المشغلات

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | للاستخدام الداخلي فقط! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | للاستخدام الداخلي فقط! |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر IOperatorSelector لمعالجة المشغلات. |
| [add](#add-java.lang.Iterable-) | يضيف إلى المجموعة جميع العوامل من مجموعة أخرى. |
| [add](#add-com.aspose.pdf.Operator-) | <p> يضيف عاملًا جديدًا إلى المجموعة. </p> <hr> <p> يوضح المثال كيفية إضافة العوامل إلى نهاية page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> إضافة العوامل في نهاية عوامل المحتوى. </p> <hr> <p> يوضح المثال كيفية إضافة عامل إلى نهاية محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا ينبغي أن يسبب التغيير تحديث المحتوى. |
| [clear](#clear--) | <p> يزيل جميع العوامل من القائمة. </p> <hr> <p> يوضح المثال كيفية مسح محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [contains](#contains-com.aspose.pdf.Operator-) | يعيد true إذا كانت المجموعة تحتوي على العامل المحدد. |
| [delete](#delete-int-) | <p> يحذف العامل من المجموعة. </p> <hr> <p> يوضح المثال كيفية حذف العامل حسب فهرسه. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | يحذف العوامل من المجموعة. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> يحذف العوامل من المجموعة. </p> <hr> <p> يوضح المثال كيفية إزالة عامل من محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | الإصدار الداخلي غير المقيد من Delete(index) |
| [dispose](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [get_Item](#get_Item-int-) | <p> يحصل على العامل حسب فهرسه. </p> <hr> مثال يوضح كيفية الحصول على عامل محتوى الصفحة حسب الفهرس. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | الإصدار الداخلي غير المقيد من الفهرس |
| [insert](#insert-int-java.lang.Iterable-) | إدراج العوامل في الموضع المحدد. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> يدرج عاملًا في المجموعة. </p> <hr> <p> يوضح المثال كيفية إدراج عامل إلى محتوى الصفحة. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> إدراج العوامل في الموضع المحدد. </p> <hr> <p> يوضح المثال كيفية إدراج عامل إلى محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | يحصل على حالة القوس لسلسلة العوامل، أي ما إذا كانت هذه العوامل داخل كتل q - Q |
| [isCommandsParsed](#isCommandsParsed--) | يحصل على الأوامر التي تم تحليلها |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [iterator](#iterator--) | يعيد عدّادًا للمجموعة |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | احصل على عدد العوامل التي تصف محتوى الصفحة دون تهيئتها. |
| [remove](#remove-com.aspose.pdf.Operator-) | إزالة عامل من المجموعة. |
| [replace](#replace-java.lang.Iterable-) | استبدال العوامل في المجموعة بعوامل أخرى. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | استبدال العوامل في المجموعة بعوامل أخرى. |
| [resumeUpdate](#resumeUpdate--) | يستأنف تحديث المستند. يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة. |
| [resumeUpdate](#resumeUpdate-boolean-) | يستأنف تحديث المستند. يحدث تدفق المحتويات في حال وجود أي تغييرات معلقة. يضع علامة "changed" على جميع المشغلات إذا كان معامل invalidate صحيحًا. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | يضبط المشغل حسب فهرسه. |
| [size](#size--) | يحصل على عدد المشغلات في المجموعة. |
| [suppressUpdate](#suppressUpdate--) | يكبت بيانات تحديث المحتويات. لا يتم تحديث تدفق المحتويات حتى يتم استدعاء ResumeUpdate. |
| [toList](#toList--) | يعيد قائمة المشغلات. |
| [toString](#toString--) | يعيد تمثيل النص للمشغل. |
| [updateData](#updateData--) | تحديث تدفق الكائن. |
| [updateNormalizedData](#updateNormalizedData--) | تحديث تدفق الكائن مع إصلاح المشغلات الغائبة GSave/GRestore. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
للاستخدام الداخلي فقط!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
للاستخدام الداخلي فقط!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر IOperatorSelector لمعالجة المشغلات.

### add {#add-java.lang.Iterable-}
يضيف إلى المجموعة جميع العوامل من مجموعة أخرى.

### add {#add-com.aspose.pdf.Operator-}
<p> يضيف عاملًا جديدًا إلى المجموعة. </p> <hr> <p> يوضح المثال كيفية إضافة العوامل إلى نهاية page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> إضافة العوامل في نهاية عوامل المحتوى. </p> <hr> <p> يوضح المثال كيفية إضافة عامل إلى نهاية محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا ينبغي أن يسبب التغيير تحديث المحتوى.

### clear {#clear--}
```
public void clear()
```

<p> يزيل جميع العوامل من القائمة. </p> <hr> <p> يوضح المثال كيفية مسح محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة.

### contains {#contains-com.aspose.pdf.Operator-}
يعيد true إذا كانت المجموعة تحتوي على العامل المحدد.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> يحذف العامل من المجموعة. </p> <hr> <p> يوضح المثال كيفية حذف العامل حسب فهرسه. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس المشغل الذي يجب حذفه. يبدأ ترقيم المشغلات من 1. |

### delete {#delete-java.lang.Iterable-}
يحذف العوامل من المجموعة.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> يحذف العوامل من المجموعة. </p> <hr> <p> يوضح المثال كيفية إزالة عامل من محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

الإصدار الداخلي غير المقيد من Delete(index)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة int |

### dispose {#dispose--}
```
public final void dispose()
```

ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> يحصل على العامل حسب فهرسه. </p> <hr> مثال يوضح كيفية الحصول على عامل محتوى الصفحة حسب الفهرس. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

الإصدار الداخلي غير المقيد من الفهرس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة int |

**Returns:**
كائن المشغل

### insert {#insert-int-java.lang.Iterable-}
إدراج العوامل في الموضع المحدد.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> يدرج عاملًا في المجموعة. </p> <hr> <p> يوضح المثال كيفية إدراج عامل إلى محتوى الصفحة. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> إدراج العوامل في الموضع المحدد. </p> <hr> <p> يوضح المثال كيفية إدراج عامل إلى محتوى الصفحة. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

يحصل على حالة القوس لسلسلة العوامل، أي ما إذا كانت هذه العوامل داخل كتل q - Q

**Returns:**
قيمة منطقية

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

يحصل على الأوامر التي تم تحليلها

**Returns:**
قيمة منطقية

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

يعيد عدّادًا للمجموعة

**Returns:**
عداد المجموعة

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

احصل على عدد العوامل التي تصف محتوى الصفحة دون تهيئتها.

**Returns:**
قيمة int

### remove {#remove-com.aspose.pdf.Operator-}
إزالة عامل من المجموعة.

### replace {#replace-java.lang.Iterable-}
استبدال العوامل في المجموعة بعوامل أخرى.

### replace {#replace-com.aspose.pdf.Operator:A-}
استبدال العوامل في المجموعة بعوامل أخرى.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

يستأنف تحديث المستند. يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

يستأنف تحديث المستند. يحدث تدفق المحتويات في حال وجود أي تغييرات معلقة. يضع علامة "changed" على جميع المشغلات إذا كان معامل invalidate صحيحًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| updateAll |  | إذا كان صحيحًا، يتم وضع علامة على جميع المشغلات في المجموعة كـ محدثة. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
يضبط المشغل حسب فهرسه.

### size {#size--}
```
public int size()
```

يحصل على عدد المشغلات في المجموعة.

**Returns:**
قيمة int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

يكبت بيانات تحديث المحتويات. لا يتم تحديث تدفق المحتويات حتى يتم استدعاء ResumeUpdate.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

يعيد قائمة المشغلات.

**Returns:**
قائمة المشغلات.

### toString {#toString--}
```
public String toString()
```

يعيد تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.

### updateData {#updateData--}
```
public void updateData()
```

تحديث تدفق الكائن.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

تحديث تدفق الكائن مع إصلاح المشغلات الغائبة GSave/GRestore.
