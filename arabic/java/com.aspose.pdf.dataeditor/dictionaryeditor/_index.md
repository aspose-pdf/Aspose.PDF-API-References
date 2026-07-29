---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة للوصول إلى قاموس شجرة المستند (قاموس المستند، قاموس الصفحة، قاموس الموارد)."
type: docs
weight: 70
url: /ar/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

فئة للوصول إلى قاموس شجرة المستند (قاموس المستند، قاموس الصفحة، قاموس الموارد).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException الموارد فارغة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | عيّن ICosPdfPrimitive إلى القاموس. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | عيّن {@link ICosPdfPrimitive} إلى القاموس. |
| [clear](#clear--) | يزيل جميع العناصر من {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يحدد ما إذا كان DictionaryEditor يحتوي على قيمة محددة. |
| [containsKey](#containsKey-java.lang.String-) | يحدد ما إذا كان {@link DictionaryEditor} يحتوي على عنصر بالمفتاح المحدد. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ينسخ عناصر DictionaryEditor إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [get_Item](#get_Item-java.lang.String-) | يحصل أو يعيّن العنصر بالمفتاح المحدد. |
| [getAllKeys](#getAllKeys--) | مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتحرير وغير قابلة للتحرير. |
| [getKeys](#getKeys--) | مجموعة من المفاتيح القابلة للتحرير. |
| [getValues](#getValues--) | يحصل على {@link ICollection} التي تحتوي على القيم في {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان {@link DictionaryEditor} للقراءة فقط. |
| [iterator](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يزيل أول ظهور لكائن محدد من DictionaryEditor. |
| [remove](#remove-java.lang.String-) | يزيل العنصر بالمفتاح المحدد من {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | يحصل أو يعيّن العنصر بالمفتاح المحدد. |
| [size](#size--) | يحصل على عدد العناصر الموجودة في {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | للوصول إلى نوع بيانات بسيط مثل السلسلة، الاسم، المنطقي، الرقم. يُعيد null للأنواع الأخرى. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException الموارد فارغة.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
عيّن ICosPdfPrimitive إلى القاموس.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
عيّن {@link ICosPdfPrimitive} إلى القاموس.

### clear {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يحدد ما إذا كان DictionaryEditor يحتوي على قيمة محددة.

### containsKey {#containsKey-java.lang.String-}
يحدد ما إذا كان {@link DictionaryEditor} يحتوي على عنصر بالمفتاح المحدد.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ينسخ عناصر DictionaryEditor إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

### get_Item {#get_Item-java.lang.String-}
يحصل أو يعيّن العنصر بالمفتاح المحدد.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتحرير وغير قابلة للتحرير.

**Returns:**
قابل للتكرار من كائن String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

مجموعة من المفاتيح القابلة للتحرير.

**Returns:**
قابل للتكرار من كائن String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

يحصل على {@link ICollection} التي تحتوي على القيم في {@link DictionaryEditor}.

**Returns:**
قابل للتكرار من كائن ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان {@link DictionaryEditor} للقراءة فقط.

**Returns:**
صحيح إذا كان {@link DictionaryEditor} للقراءة فقط؛ وإلا، خطأ.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**Returns:**
enumerator يمكن استخدامه للتكرار عبر المجموعة.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يزيل أول ظهور لكائن محدد من DictionaryEditor.

### remove {#remove-java.lang.String-}
يزيل العنصر بالمفتاح المحدد من {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
يحصل أو يعيّن العنصر بالمفتاح المحدد.

### size {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة في {@link DictionaryEditor}.

**Returns:**
قيمة int

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
للوصول إلى نوع بيانات بسيط مثل السلسلة، الاسم، المنطقي، الرقم. يُعيد null للأنواع الأخرى.
