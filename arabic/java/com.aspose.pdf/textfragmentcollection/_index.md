---
title: "TextFragmentCollection"
linktitle: "TextFragmentCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مجموعة شظايا النص"
type: docs
weight: 5130
url: /ar/java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextFragmentCollection

**All Implemented Interfaces:**
قابل للتكرار < TextFragment >

```
public final class TextFragmentCollection extends Object implements Iterable < TextFragment >
```

يمثل مجموعة شظايا النص

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.TextFragment-) | يضيف عنصر مقطع النص في الفهرس المحدد. |
| [clear](#clear--) | يمسح جميع العناصر من المجموعة. |
| [contains](#contains-com.aspose.pdf.TextFragment-) | يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [copyTo](#copyTo-com.aspose.pdf.TextFragment:A-int-) | / * / * يعيد عدادًا للمجموعة بأكملها. / * / * |
| [get_Item](#get_Item-int-) | يحصل على عنصر مقطع النص في الفهرس المحدد. يجب أن يكون الفهرس في النطاق [1..n] حيث n يساوي عدد مقاطع النص. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن للخيوط). |
| [iterator](#iterator--) | يعيد عدّادًا للمجموعة بالكامل. |
| [remove](#remove-com.aspose.pdf.TextFragment-) | يحذف العنصر المحدد من المجموعة. |
| [size](#size--) | يحصل على عدد عناصر كائن {@code TextFragment} الموجودة فعليًا في المجموعة. |

### add {#add-com.aspose.pdf.TextFragment-}
يضيف عنصر مقطع النص في الفهرس المحدد.

### clear {#clear--}
```
public void clear()
```

يمسح جميع العناصر من المجموعة.

### contains {#contains-com.aspose.pdf.TextFragment-}
يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة.

### copyTo {#copyTo-com.aspose.pdf.TextFragment:A-int-}
/ * / * يعيد عدادًا للمجموعة بأكملها. / * / *

### get_Item {#get_Item-int-}
```
public TextFragment get_Item(int index)
```

يحصل على عنصر مقطع النص في الفهرس المحدد. يجب أن يكون الفهرس في النطاق [1..n] حيث n يساوي عدد مقاطع النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس داخل المجموعة. |

**Returns:**
كائن TextFragment.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة.

**Returns:**
عنصر Object

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

### iterator {#iterator--}
```
public Iterator < TextFragment > iterator()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### remove {#remove-com.aspose.pdf.TextFragment-}
يحذف العنصر المحدد من المجموعة.

### size {#size--}
```
public int size()
```

يحصل على عدد عناصر كائن {@code TextFragment} الموجودة فعليًا في المجموعة.

**Returns:**
قيمة int
