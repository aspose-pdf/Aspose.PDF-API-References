---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل مجموعة الخطوط. </p> <hr> <pre> يوضح المثال كيفية جعل جميع الخطوط المعلنة في الصفحة مدمجة. // Open document Document doc = new.</pre>"
type: docs
weight: 1670
url: /ar/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> يمثل مجموعة الخطوط. </p> <hr> <pre> يوضح المثال كيفية جعل جميع الخطوط المعلنة في الصفحة مدمجة. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> تُستخدم مجموعات الخطوط التي تمثلها الفئة {@code FontCollection} في عدة سيناريوهات. على سبيل المثال، في الموارد التي تحتوي على خاصية {@code Resources.Fonts}. </p>

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | يضيف الخط إلى المجموعة. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | يضيف خطًا جديدًا إلى موارد الخطوط ويعيد الاسم المعين تلقائيًا لمورد الخط. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | إضافة خط جديد إلى مجموعة الخطوط. |
| [add](#add-java.lang.String-java.lang.String-) | يضيف إلى موارد الخطوط إدخال خط جديد بالاسم الأساسي المحدد للخط. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * يضيف الخط إلى المجموعة. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [contains](#contains-java.lang.String-) | يتحقق مما إذا كان الخط موجودًا في مجموعة الخطوط. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد للمصفوفة الهدف. |
| [delete](#delete-java.lang.String-) | يحذف الخط بالاسم المحدد للمورد |
| [get_Item](#get_Item-int-) | يحصل على عنصر الخط في الفهرس المحدد. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على الخط من المجموعة حسب اسم الخط. يتم رمي استثناء إذا لم يتم العثور على الخط. |
| [getFontsDictionary](#getFontsDictionary--) | احصل على كائن IPdfDictionary |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن للخيوط). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | يعيد عدّادًا للمجموعة بالكامل. |
| [iterator](#iterator--) | يعيد عدّادًا للمجموعة بالكامل. |
| [remove](#remove-com.aspose.pdf.Font-) | يحذف العنصر المحدد من المجموعة. |
| [size](#size--) | يحصل على عدد عناصر كائن {@code Font} الموجودة فعليًا في المجموعة. |

### add {#add-com.aspose.pdf.Font-}
يضيف الخط إلى المجموعة.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
يضيف خطًا جديدًا إلى موارد الخطوط ويعيد الاسم المعين تلقائيًا لمورد الخط.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
إضافة خط جديد إلى مجموعة الخطوط.

### add {#add-java.lang.String-java.lang.String-}
يضيف إلى موارد الخطوط إدخال خط جديد بالاسم الأساسي المحدد للخط.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * يضيف الخط إلى المجموعة. / * / *

### contains {#contains-com.aspose.pdf.Font-}
يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة.

### contains {#contains-java.lang.String-}
يتحقق مما إذا كان الخط موجودًا في مجموعة الخطوط.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد للمصفوفة الهدف.

### delete {#delete-java.lang.String-}
يحذف الخط بالاسم المحدد للمورد

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

يحصل على عنصر الخط في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس داخل المجموعة. |

**Returns:**
كائن الخط.

### get_Item {#get_Item-java.lang.String-}
يحصل على الخط من المجموعة حسب اسم الخط. يتم رمي استثناء إذا لم يتم العثور على الخط.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

احصل على كائن IPdfDictionary

**Returns:**
كائن IPdfDictionary

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة.

**Returns:**
كائن للمزامنة

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن للخيوط).

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### remove {#remove-com.aspose.pdf.Font-}
يحذف العنصر المحدد من المجموعة.

### size {#size--}
```
public int size()
```

يحصل على عدد عناصر كائن {@code Font} الموجودة فعليًا في المجموعة.

**Returns:**
قيمة int
