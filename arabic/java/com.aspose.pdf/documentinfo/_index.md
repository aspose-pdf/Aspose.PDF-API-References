---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل المعلومات الوصفية لمستند PDF."
type: docs
weight: 1160
url: /ar/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

يمثل المعلومات الوصفية لمستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | تهيئة كائن DocumentInfo. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | يضيف عنصرًا بالمفتاح والقيمة المحددين إلى المجموعة. |
| [clear](#clear--) | يمسح معلومات المستند. |
| [clearCustomData](#clearCustomData--) | يمسح البيانات المخصصة فقط، ويترك جميع القيم المعرفة مسبقًا الأخرى (Title, Author، إلخ). |
| [get_Item](#get_Item-java.lang.String-) | يحصل على القيمة المرتبطة بالمفتاح المحدد. |
| [getAuthor](#getAuthor--) | يحصل على مؤلف المستند. |
| [getCreationDate](#getCreationDate--) | يحصل على تاريخ إنشاء المستند. |
| [getCreationTimeZone](#getCreationTimeZone--) | منطقة التوقيت لتاريخ الإنشاء بالمللي ثانية. |
| [getCreator](#getCreator--) | يحصل على منشئ المستند. |
| [getKeywords](#getKeywords--) | يحصل على الكلمات المفتاحية للمستند. |
| [getModDate](#getModDate--) | يحصل على تاريخ تعديل المستند. |
| [getModTimeZone](#getModTimeZone--) | منطقة التوقيت لتاريخ التعديل. |
| [getProducer](#getProducer--) | يحصل على منتج المستند. |
| [getSubject](#getSubject--) | يحصل على موضوع المستند. |
| [getTitle](#getTitle--) | يحصل على عنوان المستند. |
| [getTrapped](#getTrapped--) | يحصل على علامة trapped. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | يحدد ما إذا كان المفتاح معرفًا مسبقًا (Title, Author، إلخ)، وليس مخصصًا. |
| [remove](#remove-java.lang.String-) | يزيل العنصر بالمفتاح المحدد من المجموعة. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | يضبط القيمة المرتبطة بالمفتاح المحدد. |
| [setAuthor](#setAuthor-java.lang.String-) | يضبط مؤلف المستند. |
| [setCreationDate](#setCreationDate-java.util.Date-) | يضبط تاريخ إنشاء المستند. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | منطقة التوقيت لتاريخ الإنشاء بالمللي ثانية. |
| [setCreator](#setCreator-java.lang.String-) | يضبط منشئ المستند. |
| [setKeywords](#setKeywords-java.lang.String-) | ضبط الكلمات المفتاحية للمستند. |
| [setModDate](#setModDate-java.util.Date-) | يضبط تاريخ تعديل المستند. |
| [setModTimeZone](#setModTimeZone-double-) | منطقة التوقيت لتاريخ التعديل. |
| [setProducer](#setProducer-java.lang.String-) | يضبط مُنتج المستند. |
| [setSubject](#setSubject-java.lang.String-) | يضبط موضوع المستند. |
| [setTitle](#setTitle-java.lang.String-) | يضبط عنوان المستند. |
| [setTrapped](#setTrapped-java.lang.String-) | يضبط علامة الحجز. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
تهيئة كائن DocumentInfo.

### addItem {#addItem-java.lang.String-java.lang.String-}
يضيف عنصرًا بالمفتاح والقيمة المحددين إلى المجموعة.

### clear {#clear--}
```
public void clear()
```

يمسح معلومات المستند.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

يمسح البيانات المخصصة فقط، ويترك جميع القيم المعرفة مسبقًا الأخرى (Title, Author، إلخ).

### get_Item {#get_Item-java.lang.String-}
يحصل على القيمة المرتبطة بالمفتاح المحدد.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

يحصل على مؤلف المستند.

**Returns:**
قيمة سلسلة

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

يحصل على تاريخ إنشاء المستند.

**Returns:**
كائن Date

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

منطقة التوقيت لتاريخ الإنشاء بالمللي ثانية.

**Returns:**
قيمة double

### getCreator {#getCreator--}
```
public String getCreator()
```

يحصل على منشئ المستند.

**Returns:**
قيمة سلسلة

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

يحصل على الكلمات المفتاحية للمستند.

**Returns:**
قيمة سلسلة

### getModDate {#getModDate--}
```
public Date getModDate()
```

يحصل على تاريخ تعديل المستند.

**Returns:**
كائن Date

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

منطقة التوقيت لتاريخ التعديل.

**Returns:**
قيمة double

### getProducer {#getProducer--}
```
public String getProducer()
```

يحصل على منتج المستند.

**Returns:**
قيمة سلسلة

### getSubject {#getSubject--}
```
public String getSubject()
```

يحصل على موضوع المستند.

**Returns:**
قيمة سلسلة

### getTitle {#getTitle--}
```
public String getTitle()
```

يحصل على عنوان المستند.

**Returns:**
قيمة سلسلة

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

يحصل على علامة trapped.

**Returns:**
قيمة سلسلة

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
يحدد ما إذا كان المفتاح معرفًا مسبقًا (Title, Author، إلخ)، وليس مخصصًا.

### remove {#remove-java.lang.String-}
يزيل العنصر بالمفتاح المحدد من المجموعة.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
يضبط القيمة المرتبطة بالمفتاح المحدد.

### setAuthor {#setAuthor-java.lang.String-}
يضبط مؤلف المستند.

### setCreationDate {#setCreationDate-java.util.Date-}
يضبط تاريخ إنشاء المستند.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

منطقة التوقيت لتاريخ الإنشاء بالمللي ثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | بالملي ثانية |

### setCreator {#setCreator-java.lang.String-}
يضبط منشئ المستند.

### setKeywords {#setKeywords-java.lang.String-}
ضبط الكلمات المفتاحية للمستند.

### setModDate {#setModDate-java.util.Date-}
يضبط تاريخ تعديل المستند.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

منطقة التوقيت لتاريخ التعديل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setProducer {#setProducer-java.lang.String-}
يضبط مُنتج المستند.

### setSubject {#setSubject-java.lang.String-}
يضبط موضوع المستند.

### setTitle {#setTitle-java.lang.String-}
يضبط عنوان المستند.

### setTrapped {#setTrapped-java.lang.String-}
يضبط علامة الحجز.
