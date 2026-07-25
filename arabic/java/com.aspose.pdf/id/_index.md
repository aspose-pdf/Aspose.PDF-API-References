---
title: "Id"
linktitle: "Id"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل بنية معرّف الملف. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /ar/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> يمثل بنية معرف الملف. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getModified](#getModified--) | تغيير المعرف بناءً على محتويات المستند في الوقت الذي تم فيه آخر تحديث. |
| [getOriginal](#getOriginal--) | معرف دائم بناءً على محتويات المستند في الوقت الذي تم إنشاؤه فيه أصلاً. |

### getModified {#getModified--}
```
public String getModified()
```

تغيير المعرف بناءً على محتويات المستند في الوقت الذي تم فيه آخر تحديث.

**Returns:**
قيمة سلسلة

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

معرف دائم بناءً على محتويات المستند في الوقت الذي تم إنشاؤه فيه أصلاً.

**Returns:**
قيمة سلسلة
