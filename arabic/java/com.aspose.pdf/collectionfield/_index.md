---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة حقل مخطط مجموعة المستندات."
type: docs
weight: 620
url: /ar/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

يمثل فئة حقل مخطط مجموعة المستندات.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getE](#getE--) | يحصل على علم يشير إلى ما إذا كان معالج PDF التفاعلي يجب أن يوفر دعمًا لتحرير قيمة الحقل. القيمة الافتراضية: false |
| [getFiledType](#getFiledType--) | يحصل على نوع قيمة الحقل في مجموعة المخطط. يصف هذا الحقل نوع القيمة المقابلة لـ {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | يحصل على اسم الحقل النصي الذي سيُعرض على المستخدم بواسطة معالج PDF التفاعلي |
| [getO](#getO--) | يحصل على الترتيب النسبي لاسم الحقل في واجهة المستخدم. يجب أن يتم فرز الحقول بواسطة معالج PDF التفاعلي بترتيب تصاعدي. |
| [getSubtype](#getSubtype--) | يحصل على النوع الفرعي لقيمة الحقل في مجموعة المخطط. النوع الفرعي لحقل المجموعة أو الحقل المتعلق بالملف الذي يصفه هذا القاموس. يحدد هذا الإدخال نوع البيانات التي يجب تخزينها في الحقل. |
| [getV](#getV--) | يحصل على رؤية الحقل الأولية في واجهة المستخدم. القيمة الافتراضية: true. |

### getE {#getE--}
```
public final boolean getE()
```

يحصل على علم يشير إلى ما إذا كان معالج PDF التفاعلي يجب أن يوفر دعمًا لتحرير قيمة الحقل. القيمة الافتراضية: false

**Returns:**
قيمة منطقية

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

يحصل على نوع قيمة الحقل في مجموعة المخطط. يصف هذا الحقل نوع القيمة المقابلة لـ {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
عنصر FieldValueType

### getN {#getN--}
```
public final String getN()
```

يحصل على اسم الحقل النصي الذي سيُعرض على المستخدم بواسطة معالج PDF التفاعلي

**Returns:**
قيمة سلسلة

### getO {#getO--}
```
public final Integer [] getO()
```

يحصل على الترتيب النسبي لاسم الحقل في واجهة المستخدم. يجب أن يتم فرز الحقول بواسطة معالج PDF التفاعلي بترتيب تصاعدي.

**Returns:**
مصفوفة من Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

يحصل على النوع الفرعي لقيمة الحقل في مجموعة المخطط. النوع الفرعي لحقل المجموعة أو الحقل المتعلق بالملف الذي يصفه هذا القاموس. يحدد هذا الإدخال نوع البيانات التي يجب تخزينها في الحقل.

**Returns:**
عنصر CollectionFieldSubtype

### getV {#getV--}
```
public final boolean getV()
```

يحصل على رؤية الحقل الأولية في واجهة المستخدم. القيمة الافتراضية: true.

**Returns:**
قيمة منطقية
