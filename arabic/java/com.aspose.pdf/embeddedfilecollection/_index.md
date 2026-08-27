---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل مجموعة الملفات المضمنة."
type: docs
weight: 1200
url: /ar/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
قابل للتكرار < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

فئة تمثل مجموعة الملفات المضمنة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | يضيف مواصفة الملف المضمّن إلى المجموعة. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | يضيف ملفًا إلى الملفات المضمّنة بالمفتاح المحدد. |
| [clear](#clear--) | إزالة جميع الملفات المضمنة من المستند. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | يحدد ما إذا كانت المجموعة تحتوي على FileSpecification المحدد. غير مدعوم. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | ينسخ مصفوفة كائن FileSpecification إلى colleciton. |
| [delete](#delete--) | إزالة جميع الملفات المضمنة من المستند. |
| [delete](#delete-java.lang.String-) | إزالة جميع الملفات المضمنة من المستند. |
| [deleteByKey](#deleteByKey-java.lang.String-) | يحذف الملف من المجموعة باستخدام مفتاحه في المجموعة. |
| [findByName](#findByName-java.lang.String-) | يعيد الملف المضمن بناءً على اسمه. |
| [get_Item](#get_Item-int-) | يحصل على الملف المضمن بناءً على فهرسه. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على الملف المضمن بناءً على اسمه. |
| [getKeys](#getKeys--) | يعيد قائمة مفاتيح مرفقات الملفات. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | تحقق مما إذا كانت بنية الملفات المضمنة موجودة. إرجاع TRUE إذا كانت البنية موجودة، و FALSE إذا لم تكن كذلك. إذا لم يحتوي المستند أبداً على ملفات مضمنة - لم يتم إنشاء هذه البنية وكانت غائبة. |
| [isReadOnly](#isReadOnly--) | يحدد ما إذا كانت المجموعة للقراءة فقط. دائمًا تُرجع false. |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | يعيد colleciton enumerator. |
| [iterator](#iterator--) | يعيد colleciton enumerator. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | يزيل FileSpecification المحدد من المجموعة. غير مدعوم. |
| [size](#size--) | يحصل على عدد الملفات المضمنة في المجموعة. |

### add {#add-com.aspose.pdf.FileSpecification-}
يضيف مواصفة الملف المضمّن إلى المجموعة.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
يضيف ملفًا إلى الملفات المضمّنة بالمفتاح المحدد.

### clear {#clear--}
```
public void clear()
```

إزالة جميع الملفات المضمنة من المستند.

### contains {#contains-com.aspose.pdf.FileSpecification-}
يحدد ما إذا كانت المجموعة تحتوي على FileSpecification المحدد. غير مدعوم.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
ينسخ مصفوفة كائن FileSpecification إلى colleciton.

### delete {#delete--}
```
public void delete()
```

إزالة جميع الملفات المضمنة من المستند.

### delete {#delete-java.lang.String-}
إزالة جميع الملفات المضمنة من المستند.

### deleteByKey {#deleteByKey-java.lang.String-}
يحذف الملف من المجموعة باستخدام مفتاحه في المجموعة.

### findByName {#findByName-java.lang.String-}
يعيد الملف المضمن بناءً على اسمه.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

يحصل على الملف المضمن بناءً على فهرسه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الملف المضمن. يبدأ الترقيم من 1. |

**Returns:**
مواصفات الملف المضمن المسترجعة

### get_Item {#get_Item-java.lang.String-}
يحصل على الملف المضمن بناءً على اسمه.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

يعيد قائمة مفاتيح مرفقات الملفات.

**Returns:**
قائمة قيم String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة.

**Returns:**
كائن للمزامنة

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

تحقق مما إذا كانت بنية الملفات المضمنة موجودة. إرجاع TRUE إذا كانت البنية موجودة، و FALSE إذا لم تكن كذلك. إذا لم يحتوي المستند أبداً على ملفات مضمنة - لم يتم إنشاء هذه البنية وكانت غائبة.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحدد ما إذا كانت المجموعة للقراءة فقط. دائمًا تُرجع false.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط).

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

يعيد colleciton enumerator.

**Returns:**
عداد colleciton.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

يعيد colleciton enumerator.

**Returns:**
عداد colleciton.

### remove {#remove-com.aspose.pdf.FileSpecification-}
يزيل FileSpecification المحدد من المجموعة. غير مدعوم.

### size {#size--}
```
public int size()
```

يحصل على عدد الملفات المضمنة في المجموعة.

**Returns:**
قيمة int
