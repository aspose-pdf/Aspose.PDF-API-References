---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الموقع في مستند PDF حيث ظهر خطأ استخراج النص."
type: docs
weight: 5050
url: /ar/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

يمثل الموقع في مستند PDF حيث ظهر خطأ استخراج النص.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | المفتاح (الاسم) لكائن خط PDF المستخدم لعرض العملية التي تسبب خطأ استخراج النص. |
| [getFormKey](#getFormKey--) | المفتاح (الاسم) لكائن PDF Form XObject الذي تم تحديد خطأ استخراج النص في تدفق المحتويات فيه. لا يكون فارغًا إذا كان ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | نوع كائن PDF (صفحة أو xForm) الذي تم تحديد خطأ استخراج النص في تدفق المحتويات فيه. |
| [getOperatorIndex](#getOperatorIndex--) | فهرس العملية التي تعرض النص في تدفق المحتويات (مجموعة العمليات) التي تسبب خطأ استخراج النص. |
| [getOperatorString](#getOperatorString--) | عملية عرض النص التي تسبب خطأ استخراج النص. |
| [getPageNumber](#getPageNumber--) | رقم صفحة المستند التي تم فيها تحديد خطأ استخراج النص. |
| [getPath](#getPath--) | موقع مستند PDF الذي ظهر فيه خطأ استخراج النص. |
| [getTextStartPoint](#getTextStartPoint--) | المفتاح (الاسم) لكائن خط PDF المستخدم لعرض العملية التي تسبب خطأ استخراج النص. |
| [toString](#toString--) | يرجع تمثيل النص. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

المفتاح (الاسم) لكائن خط PDF المستخدم لعرض العملية التي تسبب خطأ استخراج النص.

**Returns:**
قيمة سلسلة

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

المفتاح (الاسم) لكائن PDF Form XObject الذي تم تحديد خطأ استخراج النص في تدفق المحتويات فيه. لا يكون فارغًا إذا كان ObjectType == 'xForm'.

**Returns:**
قيمة سلسلة

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

نوع كائن PDF (صفحة أو xForm) الذي تم تحديد خطأ استخراج النص في تدفق المحتويات فيه.

**Returns:**
قيمة سلسلة

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

فهرس العملية التي تعرض النص في تدفق المحتويات (مجموعة العمليات) التي تسبب خطأ استخراج النص.

**Returns:**
قيمة int

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

عملية عرض النص التي تسبب خطأ استخراج النص.

**Returns:**
قيمة سلسلة

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

رقم صفحة المستند التي تم فيها تحديد خطأ استخراج النص.

**Returns:**
قيمة int

### getPath {#getPath--}
```
public String getPath()
```

موقع مستند PDF الذي ظهر فيه خطأ استخراج النص.

**Returns:**
قيمة سلسلة

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

المفتاح (الاسم) لكائن خط PDF المستخدم لعرض العملية التي تسبب خطأ استخراج النص.

**Returns:**
مثيل Point

### toString {#toString--}
```
public String toString()
```

يرجع تمثيل النص.

**Returns:**
تمثيل كسلسلة.
