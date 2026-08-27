---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة للوصول إلى قاموس كائن."
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

فئة للوصول إلى قاموس كائن.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | ينشئ قاموسًا من الموارد. @exception ArgumentNullException الموارد فارغة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | عيّن ICosPdfPrimitive إلى القاموس. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | عيّن {@link ICosPdfPrimitive} في القاموس. @exception ArgumentException أطلق استثناءً إذا تعذّر تعديل أو إزالة المفتاح/القيمة. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | أضف زوجًا من العناصر. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | أضف عنصرًا. |
| [clear](#clear--) | يزيل جميع العناصر من {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يحدد ما إذا كان CosPdfDictionary يحتوي على قيمة محددة. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | إرجاع true إذا كان يحتوي على عنصر |
| [containsKey](#containsKey-java.lang.String-) | يحدد ما إذا كان {@link CosPdfDictionary} يحتوي على عنصر بالمفتاح المحدد. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ينسخ عناصر CosPdfDictionary إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | نسخ إلى مصفوفة |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | ينشئ قاموسًا فارغًا سيتم ربطه بالمستند. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | ينشئ قاموسًا فارغًا سيتم ربطه بالصفحة. |
| [get_Item](#get_Item-java.lang.String-) | يحصل أو يعيّن العنصر بالمفتاح المحدد. |
| [getAllKeys](#getAllKeys--) | مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتحرير وغير قابلة للتحرير. |
| [getKeys](#getKeys--) | مجموعة من المفاتيح القابلة للتحرير. |
| [getValues](#getValues--) | يحصل على {@link ICollection} يحتوي على القيم في {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان {@link CosPdfDictionary} للقراءة فقط. |
| [iterator](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يزيل الظهور الأول لكائن محدد من CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | يزيل العنصر بالمفتاح المحدد من {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | إزالة العنصر |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | إزالة العنصر بالمفتاح. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | يحصل أو يضبط العنصر بالمفتاح المحدد. @exception ArgumentNullException المفتاح فارغ. @exception KeyNotFoundException تم استرجاع الخاصية ولم يتم العثور على المفتاح. @exception ArgumentException يرمي استثناء إذا لم يكن بالإمكان تعديل/ضبط المفتاح. |
| [size](#size--) | يحصل على عدد العناصر الموجودة في {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | يحاول تحويل هذه المثيلة إلى {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | للوصول إلى نوع بيانات بسيط مثل السلسلة، الاسم، المنطقي، الرقم. يُعيد null للأنواع الأخرى. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | حاول الحصول على القيمة |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
ينشئ قاموسًا من الموارد. @exception ArgumentNullException الموارد فارغة.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
عيّن ICosPdfPrimitive إلى القاموس.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
عيّن {@link ICosPdfPrimitive} في القاموس. @exception ArgumentException أطلق استثناءً إذا تعذّر تعديل أو إزالة المفتاح/القيمة.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
أضف زوجًا من العناصر.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
أضف عنصرًا.

### clear {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يحدد ما إذا كان CosPdfDictionary يحتوي على قيمة محددة.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
إرجاع true إذا كان يحتوي على عنصر

### containsKey {#containsKey-java.lang.String-}
يحدد ما إذا كان {@link CosPdfDictionary} يحتوي على عنصر بالمفتاح المحدد.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ينسخ عناصر CosPdfDictionary إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
نسخ إلى مصفوفة

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
ينشئ قاموسًا فارغًا سيتم ربطه بالمستند.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
ينشئ قاموسًا فارغًا سيتم ربطه بالصفحة.

### get_Item {#get_Item-java.lang.String-}
يحصل أو يعيّن العنصر بالمفتاح المحدد.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتحرير وغير قابلة للتحرير.

**Returns:**
قائمة قيم String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

مجموعة من المفاتيح القابلة للتحرير.

**Returns:**
قائمة قيم String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

يحصل على {@link ICollection} يحتوي على القيم في {@link CosPdfDictionary}.

**Returns:**
قائمة من مثيلات ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان {@link CosPdfDictionary} للقراءة فقط.

**Returns:**
صحيح إذا كان {@link CosPdfDictionary} للقراءة فقط؛ وإلا، خطأ.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**Returns:**
enumerator يمكن استخدامه للتكرار عبر المجموعة.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يزيل الظهور الأول لكائن محدد من CosPdfDictionary.

### remove {#remove-java.lang.String-}
يزيل العنصر بالمفتاح المحدد من {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
إزالة العنصر

### removeItemByKey {#removeItemByKey-java.lang.String-}
إزالة العنصر بالمفتاح.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
يحصل أو يضبط العنصر بالمفتاح المحدد. @exception ArgumentNullException المفتاح فارغ. @exception KeyNotFoundException تم استرجاع الخاصية ولم يتم العثور على المفتاح. @exception ArgumentException يرمي استثناء إذا لم يكن بالإمكان تعديل/ضبط المفتاح.

### size {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة في {@link CosPdfDictionary}.

**Returns:**
قيمة int

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

يحاول تحويل هذه المثيلة إلى {@link CosPdfDictionary}.

**Returns:**
null إذا لم تكن المثيلة {@link CosPdfDictionary} وإلا {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
للوصول إلى نوع بيانات بسيط مثل السلسلة، الاسم، المنطقي، الرقم. يُعيد null للأنواع الأخرى.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
حاول الحصول على القيمة
