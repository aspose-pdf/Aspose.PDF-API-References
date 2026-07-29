---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "قاموس مظهر التعليق التوضيحي يحدد كيف يجب عرض التعليق بصريًا على الصفحة."
type: docs
weight: 150
url: /ar/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

قاموس مظهر التعليق التوضيحي يحدد كيف يجب عرض التعليق بصريًا على الصفحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | يضيف عنصرًا بالمفتاح والقيمة المقدمة. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يضيف زوجًا بالمفتاح والقيمة إلى القاموس. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | أضف نموذج X للمفتاح المحدد. |
| [clear](#clear--) | يزيل جميع العناصر من القاموس. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس. |
| [containsKey](#containsKey-java.lang.String-) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * يعيد كائن IDictionaryEnumerator للقاموس. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ينسخ عناصر ICollection إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [get_Item](#get_Item-java.lang.String-) | يمثل نموذجًا ملائمًا للحصول على تدفقات المظهر. |
| [getDict](#getDict--) | يحصل على قاموس pdf |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | قيم .state لـ D)، حيث N - المظهر العادي، R - مظهر التمرير، D - مظهر الضغط وstate - اسم الحالة (مثل On، Off لأزرار الاختيار). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | قيم .state لـ D)، حيث N - المظهر العادي، R - مظهر التمرير، D - مظهر الضغط وstate - اسم الحالة (مثل On، Off لأزرار الاختيار). |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى القاموس. |
| [getValues_](#getValues_--) | يحصل على قائمة قيم القاموس. تحتوي مجموعة النتائج على قائمة كائنات XForm. |
| [getValues](#getValues--) | يحصل على قائمة قيم القاموس. تحتوي مجموعة النتائج على قائمة كائنات XForm. |
| [isFixedSize](#isFixedSize--) | يحصل على قيمة تشير إلى ما إذا كان القاموس ذو حجم ثابت. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان القاموس للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى القاموس متزامنًا (آمن للخيوط). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | المُعدِّد للمجموعة. |
| [iterator](#iterator--) | يعيد كائن IDictionaryEnumerator للقاموس. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | يزيل المفتاح من القاموس. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | يحصل على عدد العناصر الموجودة في القاموس. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |

### add {#add-java.lang.Object-java.lang.Object-}
يضيف عنصرًا بالمفتاح والقيمة المقدمة.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يضيف زوجًا بالمفتاح والقيمة إلى القاموس.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
أضف نموذج X للمفتاح المحدد.

### clear {#clear--}
```
public void clear()
```

يزيل جميع العناصر من القاموس.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس.

### containsKey {#containsKey-java.lang.String-}
يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * يعيد كائن IDictionaryEnumerator للقاموس. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ينسخ عناصر ICollection إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

### get_Item {#get_Item-java.lang.String-}
يمثل نموذجًا ملائمًا للحصول على تدفقات المظهر.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

يحصل على قاموس pdf

**Returns:**
كائن IPdfDictionary

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

يحصل على مفاتيح القاموس. إذا كان قاموس المظهر يحتوي على قواميس فرعية، فإن {@code Keys} يحتوي على قيم (N|R|D).state، حيث N - المظهر العادي، R - مظهر التمرير، D - مظهر الضغط وstate - اسم الحالة (مثل On، Off لأزرار الاختيار).

**Returns:**
قائمة قيم String

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

يحصل على مفاتيح القاموس. إذا كان قاموس المظهر يحتوي على قواميس فرعية، فإن {@code Keys} يحتوي على قيم (N|R|D).state، حيث N - المظهر العادي، R - مظهر التمرير، D - مظهر الضغط وstate - اسم الحالة (مثل On، Off لأزرار الاختيار).

**Returns:**
قائمة قيم String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى القاموس.

**Returns:**
كائن للمزامنة

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

يحصل على قائمة قيم القاموس. تحتوي مجموعة النتائج على قائمة كائنات XForm.

**Returns:**
قائمة قيم XForm

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

يحصل على قائمة قيم القاموس. تحتوي مجموعة النتائج على قائمة كائنات XForm.

**Returns:**
قائمة قيم XForm

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

يحصل على قيمة تشير إلى ما إذا كان القاموس ذو حجم ثابت.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان القاموس للقراءة فقط.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يحصل على قيمة تشير إلى ما إذا كان الوصول إلى القاموس متزامنًا (آمن للخيوط).

**Returns:**
قيمة منطقية

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

المُعدِّد للمجموعة.

**Returns:**
مُعدِّد عناصر المجموعة.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

يعيد كائن IDictionaryEnumerator للقاموس.

**Returns:**
مُعدِّد القاموس.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يزيل زوج المفتاح/القيمة من المجموعة.

### removeItemByKey {#removeItemByKey-java.lang.String-}
يزيل المفتاح من القاموس.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

يحصل على عدد العناصر الموجودة في القاموس.

**Returns:**
قيمة int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها.
