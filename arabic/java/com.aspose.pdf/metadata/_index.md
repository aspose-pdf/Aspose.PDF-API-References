---
title: "البيانات الوصفية"
linktitle: "البيانات الوصفية"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يوفر الوصول إلى تدفق بيانات XMP الوصفية."
type: docs
weight: 3050
url: /ar/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

يوفر الوصول إلى تدفق بيانات XMP الوصفية.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يضيف زوجًا بالمفتاح والقيمة إلى القاموس. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | يضيف قيمة إلى البيانات الوصفية. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | يضيف امتداد pdf إلى البيانات الوصفية. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | يضيف قيمة إلى البيانات الوصفية. |
| [clear](#clear--) | يمسح البيانات الوصفية. |
| [contains](#contains-java.lang.String-) | يتحقق مما إذا كان المفتاح موجودًا في البيانات الوصفية. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس. |
| [containsKey](#containsKey-java.lang.String-) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ عناصر المجموعة إلى مصفوفة. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ينسخ عناصر المجموعة إلى مصفوفة. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على البيانات من البيانات الوصفية. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | للاستخدام الداخلي فقط. يحصل على قاموس حقول الامتداد. |
| [getExtensionFields](#getExtensionFields--) | <p> يحصل على قاموس حقول الامتداد. </p> |
| [getItem](#getItem-java.lang.String-) | يحصل على البيانات من البيانات الوصفية. |
| [getKeys](#getKeys--) | يحصل على مجموعة مفاتيح البيانات الوصفية. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | يعيد URI مساحة الاسم حسب البادئة. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | يعيد البادئة حسب URI مساحة الاسم. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن مزامنة المجموعة. |
| [getValues](#getValues--) | يحصل على القيم في البيانات الوصفية. |
| [isFixedSize](#isFixedSize--) | يتحقق مما إذا كانت المجموعة ذات حجم ثابت. |
| [isReadOnly](#isReadOnly--) | يتحقق مما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يتحقق مما إذا كانت المجموعة متزامنة. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | يعيد عداد القاموس. |
| [iteratorIE](#iteratorIE--) | يحصل على عداد المجموعة. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | يسجل URI مساحة الاسم. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | يسجل URI مساحة الاسم. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | يزيل الإدخال من البيانات الوصفية. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | يضبط البيانات من البيانات الوصفية. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | يضبط البيانات من البيانات الوصفية. |
| [size](#size--) | يحصل على عدد العناصر في المجموعة. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يضيف زوجًا بالمفتاح والقيمة إلى القاموس.

### addItem {#addItem-java.lang.String-java.lang.Object-}
يضيف قيمة إلى البيانات الوصفية.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
يضيف امتداد pdf إلى البيانات الوصفية.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
يضيف قيمة إلى البيانات الوصفية.

### clear {#clear--}
```
public void clear()
```

يمسح البيانات الوصفية.

### contains {#contains-java.lang.String-}
يتحقق مما إذا كان المفتاح موجودًا في البيانات الوصفية.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس.

### containsKey {#containsKey-java.lang.String-}
يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
ينسخ عناصر المجموعة إلى مصفوفة.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ينسخ عناصر المجموعة إلى مصفوفة.

### get_Item {#get_Item-java.lang.String-}
يحصل على البيانات من البيانات الوصفية.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

للاستخدام الداخلي فقط. يحصل على قاموس حقول الامتداد.

**Returns:**
كائن داخلي

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> يحصل على قاموس حقول الامتداد. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} كائن

### getItem {#getItem-java.lang.String-}
يحصل على البيانات من البيانات الوصفية.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

يحصل على مجموعة مفاتيح البيانات الوصفية.

**Returns:**
ICollection كائن

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
يعيد URI مساحة الاسم حسب البادئة.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
يعيد البادئة حسب URI مساحة الاسم.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن مزامنة المجموعة.

**Returns:**
كائن للمزامنة

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

يحصل على القيم في البيانات الوصفية.

**Returns:**
ICollection كائن

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

يتحقق مما إذا كانت المجموعة ذات حجم ثابت.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يتحقق مما إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يتحقق مما إذا كانت المجموعة متزامنة.

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

يعيد عداد القاموس.

**Returns:**
المُعدِّد.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

يحصل على عداد المجموعة.

**Returns:**
IEnumerator كائن @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
يسجل URI مساحة الاسم.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
يسجل URI مساحة الاسم.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يزيل زوج المفتاح/القيمة من المجموعة.

### removeItemByKey {#removeItemByKey-java.lang.String-}
يزيل الإدخال من البيانات الوصفية.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
يضبط البيانات من البيانات الوصفية.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
يضبط البيانات من البيانات الوصفية.

### size {#size--}
```
public int size()
```

يحصل على عدد العناصر في المجموعة.

**Returns:**
قيمة int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها.
