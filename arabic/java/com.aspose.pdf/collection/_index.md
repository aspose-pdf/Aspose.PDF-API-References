---
title: "مجموعة"
linktitle: "مجموعة"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الفئة Collection (12.3.5 Collections)."
type: docs
weight: 610
url: /ar/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
قابل للتكرار < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

يمثل الفئة Collection (12.3.5 Collections).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Collection](#Collection--) | يقوم بتهيئة كائن Collection جديد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | اسم الملف المضمن الافتراضي. |
| [getSchema](#getSchema--) | يحصل على "Schema" لمجموعة مستندات. |
| [getSortedCollection](#getSortedCollection--) | يحصل على مجموعة من الملفات مرتبة وفقًا للمواصفات. |

### Collection {#Collection--}
```
public Collection()
```

يقوم بتهيئة كائن Collection جديد.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

اسم الملف المضمن الافتراضي.

**Returns:**
كائن String

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

يحصل على "Schema" لمجموعة مستندات.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

يحصل على مجموعة من الملفات مرتبة وفقًا للمواصفات.

**Returns:**
قائمة الملفات المرتبة.
