---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل مجموعة جميع الوجهات (شجرة أسماء تُطابق سلاسل الأسماء بالوجهات (انظر 12.3.2.3، \"الوجهات المسماة\") و (انظر 7.7.4، \"قاموس الأسماء\")) في."
type: docs
weight: 960
url: /ar/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

فئة تمثل مجموعة جميع الوجهات (شجرة أسماء تربط سلاسل الأسماء بالوجهات (انظر 12.3.2.3، "الوجهات المسماة") و(انظر 7.7.4، "قاموس الأسماء")) في مستند PDF.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يضيف العنصر المحدد. |
| [clear](#clear--) | المجموعة للقراءة فقط. دائمًا تُطلق استثناء NotSupportedException. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يحدد ما إذا كان هذا المثيل يحتوي على الكائن. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ينسخ عناصر المجموعة إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [get_Item](#get_Item-int-) | يحصل على كائن الوجهة حسب الفهرس. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | يرجع الوجهة الصريحة بالاسم. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | يرجع رقم صفحة الوجهة بالاسم. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يرجع فهرس الوجهة في المجموعة. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [iterator](#iterator--) | يرجع المُعدِّد. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يزيل العنصر المحدد. |
| [size](#size--) | يحصل على عدد العناصر الموجودة في المجموعة. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يضيف العنصر المحدد.

### clear {#clear--}
```
public void clear()
```

المجموعة للقراءة فقط. دائمًا تُطلق استثناء NotSupportedException.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يحدد ما إذا كان هذا المثيل يحتوي على الكائن.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ينسخ عناصر المجموعة إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

يحصل على كائن الوجهة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الوجهة المراد الحصول عليه. |

**Returns:**
الوجهة.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
يرجع الوجهة الصريحة بالاسم.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
يرجع رقم صفحة الوجهة بالاسم.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يرجع فهرس الوجهة في المجموعة.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

يرجع المُعدِّد.

**Returns:**
المُعدِّد.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يزيل العنصر المحدد.

### size {#size--}
```
public int size()
```

يحصل على عدد العناصر الموجودة في المجموعة.

**Returns:**
قيمة int
