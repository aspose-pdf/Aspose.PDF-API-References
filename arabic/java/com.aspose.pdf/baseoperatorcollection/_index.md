---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الفئة الأساسية لمجموعة المشغلين."
type: docs
weight: 270
url: /ar/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

يمثل الفئة الأساسية لمجموعة المشغلين.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | يضيف مشغلاً جديدًا إلى المجموعة. |
| [cancelUpdate](#cancelUpdate--) | يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا ينبغي أن يسبب التغيير تحديث المحتوى. |
| [clear](#clear--) | يمسح المجموعة. |
| [contains](#contains-com.aspose.pdf.Operator-) | تحقق مما إذا كان العنصر موجودًا في المجموعة. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | داخلي |
| [get_Item](#get_Item-int-) | يحصل على المشغل حسب فهرسه. |
| [getUnrestricted](#getUnrestricted-int-) | للاستخدام الداخلي فقط |
| [insert](#insert-int-com.aspose.pdf.Operator-) | يدرج المشغل في المجموعة. |
| [isEmpty](#isEmpty--) | يرجع TRUE إذا كانت المجموعة فارغة. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع |
| [isReadOnly](#isReadOnly--) | يرجع true إذا كانت المجموعة للقراءة فقط. |
| [iterator](#iterator--) | يعيد عدّادًا للمجموعة |
| [remove](#remove-com.aspose.pdf.Operator-) | يزيل المشغل من المجموعة. |
| [resumeUpdate](#resumeUpdate--) | يستأنف تحديث المستند. يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | يضبط المشغل حسب فهرسه. |
| [size](#size--) | يحصل على عدد المشغلات في المجموعة. |
| [suppressUpdate](#suppressUpdate--) | يقمع تحديث بيانات المحتوى. لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate. |
| [toList](#toList--) | يرجع قائمة المشغلات. |
| [updateData](#updateData--) | داخلي |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
يضيف مشغلاً جديدًا إلى المجموعة.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا ينبغي أن يسبب التغيير تحديث المحتوى.

### clear {#clear--}
```
public abstract void clear()
```

يمسح المجموعة.

### contains {#contains-com.aspose.pdf.Operator-}
تحقق مما إذا كان العنصر موجودًا في المجموعة.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

داخلي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة int |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

يحصل على المشغل حسب فهرسه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس المشغل. يبدأ الترقيم من 1. |

**Returns:**
المشغل من الفهرس المطلوب

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

للاستخدام الداخلي فقط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة int |

**Returns:**
كائن المشغل

### insert {#insert-int-com.aspose.pdf.Operator-}
يدرج المشغل في المجموعة.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

يرجع TRUE إذا كانت المجموعة فارغة.

**Returns:**
قيمة منطقية

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

يرجع true إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

يعيد عدّادًا للمجموعة

**Returns:**
عداد المجموعة

### remove {#remove-com.aspose.pdf.Operator-}
يزيل المشغل من المجموعة.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

يستأنف تحديث المستند. يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
يضبط المشغل حسب فهرسه.

### size {#size--}
```
public abstract int size()
```

يحصل على عدد المشغلات في المجموعة.

**Returns:**
قيمة صحيحة

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

يقمع تحديث بيانات المحتوى. لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

يرجع قائمة المشغلات.

**Returns:**
قائمة المشغلات.

### updateData {#updateData--}
```
public abstract void updateData()
```

داخلي
