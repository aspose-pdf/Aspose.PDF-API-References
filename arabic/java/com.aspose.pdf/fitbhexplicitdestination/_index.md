---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الوجهة الصريحة التي تعرض الصفحة مع إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة ومحتوى الصفحة مكبرًا فقط."
type: docs
weight: 1530
url: /ar/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي العمودي العلوي عند حافة النافذة العليا وتكبير محتوى الصفحة بما يكفي لتناسب العرض الكامل لصندوق الحدود داخل النافذة. قيمة null للعلوي تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | ينشئ النسخة ويُهيئها بواسطة كائن صفحة DOM ومعامل top. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTop](#getTop--) | يحصل على إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة. |
| [toString](#toString--) | يحول حالة الكائن إلى قيمة نصية. مثال: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
ينشئ وجهة صريحة عن بُعد.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

ينشئ وجهة صريحة عن بُعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم صفحة الوجهة للمستند البعيد. |
| أعلى |  | إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
ينشئ النسخة ويُهيئها بواسطة كائن صفحة DOM ومعامل top.

### getTop {#getTop--}
```
public double getTop()
```

يحصل على إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة.

**Returns:**
قيمة double

### toString {#toString--}
```
public String toString()
```

يحول حالة الكائن إلى قيمة نصية. مثال: "1 FitBH 100".

**Returns:**
قيمة نصية تمثل حالة الكائن.
