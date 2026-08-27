---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الوجهة الصريحة التي تعرض الصفحة بمحتوياتها مكبرة بما يكفي لتناسب المستطيل المحدد بالإحداثيات اليسار، الأسفل، اليمين، و."
type: docs
weight: 1570
url: /ar/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

يمثل وجهة صريحة تعرض الصفحة مع تكبير محتواها بما يكفي لتناسب المستطيل المحدد بالإحداثيات اليسار، الأسفل، اليمين، والعلوي بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع توسيط المستطيل داخل النافذة في البعد الآخر. قد يؤدي قيمة null لأي من المعاملات إلى سلوك غير متوقع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | ينشئ وجهة صريحة عن بُعد. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | ينشئ المثيل ويُهيئه بواسطة كائن صفحة DOM والمعلمات المرئية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBottom](#getBottom--) | يحصل على الإحداثي العمودي السفلي للمستطيل المرئي. |
| [getLeft](#getLeft--) | يحصل على الإحداثي الأفقي الأيسر للمستطيل المرئي. |
| [getRight](#getRight--) | يحصل على الإحداثي الأفقي الأيمن للمستطيل المرئي. |
| [getTop](#getTop--) | يحصل على الإحداثي العمودي العلوي للمستطيل المرئي. |
| [toString](#toString--) | يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
ينشئ وجهة صريحة عن بُعد.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

ينشئ وجهة صريحة عن بُعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم صفحة الوجهة للمستند البعيد. |
| اليسار |  | الإحداثي الأفقي الأيسر للمستطيل المرئي. |
| الأسفل |  | الإحداثي العمودي السفلي للمستطيل المرئي. |
| يمين |  | الإحداثي الأفقي الأيمن للمستطيل المرئي. |
| أعلى |  | الإحداثي العمودي العلوي للمستطيل المرئي. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
ينشئ المثيل ويُهيئه بواسطة كائن صفحة DOM والمعلمات المرئية.

### getBottom {#getBottom--}
```
public double getBottom()
```

يحصل على الإحداثي العمودي السفلي للمستطيل المرئي.

**Returns:**
قيمة double

### getLeft {#getLeft--}
```
public double getLeft()
```

يحصل على الإحداثي الأفقي الأيسر للمستطيل المرئي.

**Returns:**
قيمة double

### getRight {#getRight--}
```
public double getRight()
```

يحصل على الإحداثي الأفقي الأيمن للمستطيل المرئي.

**Returns:**
قيمة double

### getTop {#getTop--}
```
public double getTop()
```

يحصل على الإحداثي العمودي العلوي للمستطيل المرئي.

**Returns:**
قيمة double

### toString {#toString--}
```
public String toString()
```

يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 FitR 100 200 300 400".

**Returns:**
قيمة نصية تمثل حالة الكائن.
