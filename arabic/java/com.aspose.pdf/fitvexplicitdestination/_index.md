---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الوجهة الصريحة التي تعرض الصفحة مع إحداثي أفقي أيسر موضعه عند الحافة اليسرى للنافذة ومحتوى الصفحة مكبرًا فقط."
type: docs
weight: 1580
url: /ar/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي الأفقي الأيسر عند حافة النافذة اليسرى وتكبير محتوى الصفحة بما يكفي لتناسب الارتفاع الكامل للصفحة داخل النافذة. قيمة null للأيسر تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | ينشئ المثيل ويُهيئه بواسطة كائن صفحة DOM ومعامل اليسار. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLeft](#getLeft--) | يحصل على الإحداثي الأفقي الأيسر الموضع عند الحافة اليسرى للنافذة. |
| [toString](#toString--) | يحوِّل حالة الكائن إلى قيمة نصية. مثال: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
ينشئ وجهة صريحة عن بُعد.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

ينشئ وجهة صريحة عن بُعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم صفحة الوجهة للمستند البعيد. |
| اليسار |  | الإحداثي الأفقي الأيسر الموضع عند الحافة اليسرى للنافذة. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
ينشئ المثيل ويُهيئه بواسطة كائن صفحة DOM ومعامل اليسار.

### getLeft {#getLeft--}
```
public double getLeft()
```

يحصل على الإحداثي الأفقي الأيسر الموضع عند الحافة اليسرى للنافذة.

**Returns:**
قيمة double

### toString {#toString--}
```
public String toString()
```

يحوِّل حالة الكائن إلى قيمة نصية. مثال: "1 FitV 100".

**Returns:**
قيمة نصية تمثل حالة الكائن.
