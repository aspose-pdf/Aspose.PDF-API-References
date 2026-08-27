---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل نتيجة عملية تسلسل حقل النموذج."
type: docs
weight: 1390
url: /ar/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

يمثل نتيجة عملية تسلسل حقل النموذج.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | ينشئ مثيلًا جديدًا من الفئة {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة {@link FieldSerializationResult}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | يحصل على رسائل الخطأ المرتبطة بعملية التسلسل. القيمة: مجموعة من رسائل الخطأ. |
| [getFieldFullName](#getFieldFullName--) | يحصل على الاسم الكامل للحقل. القيمة: الاسم الكامل للحقل. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | يحصل على حالة تسلسل حقل النموذج. القيمة: حالة تسلسل حقل النموذج. |
| [getWarningMessages](#getWarningMessages--) | يحصل على رسائل التحذير المرتبطة بعملية التسلسل. القيمة: مجموعة من رسائل التحذير. |
| [updateStatus](#updateStatus-int-java.lang.String-) | يحدّث حالة التسلسل ويضيف رسالة إلى المجموعة المناسبة. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

ينشئ مثيلًا جديدًا من الفئة {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
ينشئ مثيلًا جديدًا من الفئة {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

يحصل على رسائل الخطأ المرتبطة بعملية التسلسل. القيمة: مجموعة من رسائل الخطأ.

**Returns:**
مجموعة HashSet من كائن String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

يحصل على الاسم الكامل للحقل. القيمة: الاسم الكامل للحقل.

**Returns:**
قيمة سلسلة

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

يحصل على حالة تسلسل حقل النموذج. القيمة: حالة تسلسل حقل النموذج.

**Returns:**
عنصر FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

يحصل على رسائل التحذير المرتبطة بعملية التسلسل. القيمة: مجموعة من رسائل التحذير.

**Returns:**
مجموعة HashSet من كائن String

### updateStatus {#updateStatus-int-java.lang.String-}
يحدّث حالة التسلسل ويضيف رسالة إلى المجموعة المناسبة.
