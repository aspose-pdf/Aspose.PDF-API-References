---
title: "FileParams"
linktitle: "FileParams"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد قاموس معلمات الملف المضمّن الذي يجب أن يحتوي على معلومات إضافية خاصة بالملف."
type: docs
weight: 1490
url: /ar/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

يحدد قاموس معلمات الملف المضمّن الذي يجب أن يحتوي على معلومات إضافية خاصة بالملف.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | منشئ لفئة FileParams. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCheckSum](#getCheckSum--) | سلسلة بطول 16 بايت تمثل المجموع الاختباري لبايتات الملف المضمن غير المضغوط. يتم حساب المجموع الاختباري بتطبيق خوارزمية MD5 القياسية على بايتات تدفق الملف المضمن. |
| [getCreationDate](#getCreationDate--) | احصل على التاريخ والوقت عندما تم إنشاء الملف المضمن. |
| [getModDate](#getModDate--) | احصل على التاريخ والوقت عندما تم تعديل الملف المضمن آخر مرة. |
| [getSize](#getSize--) | حجم الملف المضمن غير المضغوط، بالبايت. |
| [setCreationDate](#setCreationDate-java.util.Date-) | حدد التاريخ والوقت عندما تم إنشاء الملف المضمن. |
| [setModDate](#setModDate-java.util.Date-) | حدد التاريخ والوقت عندما تم تعديل الملف المضمن آخر مرة. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
منشئ لفئة FileParams.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

سلسلة بطول 16 بايت تمثل المجموع الاختباري لبايتات الملف المضمن غير المضغوط. يتم حساب المجموع الاختباري بتطبيق خوارزمية MD5 القياسية على بايتات تدفق الملف المضمن.

**Returns:**
قيمة سلسلة

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

احصل على التاريخ والوقت عندما تم إنشاء الملف المضمن.

**Returns:**
كائن Date

### getModDate {#getModDate--}
```
public Date getModDate()
```

احصل على التاريخ والوقت عندما تم تعديل الملف المضمن آخر مرة.

**Returns:**
كائن Date

### getSize {#getSize--}
```
public int getSize()
```

حجم الملف المضمن غير المضغوط، بالبايت.

**Returns:**
قيمة int

### setCreationDate {#setCreationDate-java.util.Date-}
حدد التاريخ والوقت عندما تم إنشاء الملف المضمن.

### setModDate {#setModDate-java.util.Date-}
حدد التاريخ والوقت عندما تم تعديل الملف المضمن آخر مرة.
