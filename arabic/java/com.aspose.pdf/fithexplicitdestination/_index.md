---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الوجهة الصريحة التي تعرض الصفحة مع إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة ومحتوى الصفحة مكبرًا فقط."
type: docs
weight: 1560
url: /ar/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي العمودي العلوي عند حافة النافذة العليا وتكبير محتوى الصفحة بما يكفي لتناسب العرض الكامل للصفحة داخل النافذة. قيمة null للعلوي تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | ينشئ النسخة ويُهيئها بواسطة كائن صفحة DOM ومعامل top. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTop](#getTop--) | يحصل على إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة. |
| [toString](#toString--) | يحوِّل حالة الكائن إلى قيمة نصية. مثال: "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
ينشئ وجهة صريحة عن بُعد.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

ينشئ وجهة صريحة عن بُعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم صفحة الوجهة للمستند البعيد. |
| أعلى |  | إحداثي العمودي العلوي موضعًا عند الحافة العلوية للنافذة. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
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

يحوِّل حالة الكائن إلى قيمة نصية. مثال: "1 FitH 100".

**Returns:**
قيمة نصية تمثل حالة الكائن.
