---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل الوجهة الصريحة التي تعرض الصفحة مع الإحداثيات (left, top) الموضوعة في الزاوية العليا اليسرى للنافذة ومحتويات الصفحة."
type: docs
weight: 5800
url: /ar/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> يمثل الوجهة الصريحة التي تعرض الصفحة بالإحداثيات (اليسار، الأعلى) الموضوعة في الزاوية العليا اليسرى للنافذة ومحتويات الصفحة مكبرة بمعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تشير إلى أن القيمة الحالية لهذا المعامل يجب الاحتفاظ بها دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | ينشئ وجهة صريحة عن بُعد. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | ينشئ وجهة صريحة عن بُعد. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | ينشئ المثيل ويُهيئه بواسطة كائن صفحة DOM والمعلمات المرئية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | إنشاء وجهة إلى الموقع المحدد للصفحة مع مراعاة دوران الصفحة إذا لزم الأمر. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | إنشاء وجهة إلى الصفحة المحددة. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | إنشاء وجهة إلى الزاوية العليا اليسرى للصفحة المحددة. |
| [getLeft](#getLeft--) | يحصل على الإحداثي الأفقي الأيسر للزاوية العليا اليسرى للنافذة. |
| [getTop](#getTop--) | يحصل على الإحداثي العمودي العلوي للزاوية العليا اليسرى للنافذة. |
| [getZoom](#getZoom--) | يحصل على عامل التكبير. |
| [toString](#toString--) | يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
ينشئ وجهة صريحة عن بُعد.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

ينشئ وجهة صريحة عن بُعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم صفحة الوجهة للمستند البعيد. |
| اليسار |  | الإحداثي الأفقي الأيسر للزاوية العليا اليسرى للنافذة. |
| أعلى |  | الإحداثي العمودي العلوي للزاوية العليا اليسرى للنافذة. |
| تكبير |  | عامل التكبير. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
ينشئ المثيل ويُهيئه بواسطة كائن صفحة DOM والمعلمات المرئية.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
إنشاء وجهة إلى الموقع المحدد للصفحة مع مراعاة دوران الصفحة إذا لزم الأمر.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
إنشاء وجهة إلى الصفحة المحددة.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
إنشاء وجهة إلى الزاوية العليا اليسرى للصفحة المحددة.

### getLeft {#getLeft--}
```
public double getLeft()
```

يحصل على الإحداثي الأفقي الأيسر للزاوية العليا اليسرى للنافذة.

**Returns:**
مزدوج

### getTop {#getTop--}
```
public double getTop()
```

يحصل على الإحداثي العمودي العلوي للزاوية العليا اليسرى للنافذة.

**Returns:**
مزدوج

### getZoom {#getZoom--}
```
public double getZoom()
```

يحصل على عامل التكبير.

**Returns:**
مزدوج

### toString {#toString--}
```
public String toString()
```

يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 XYZ 100 200 3".

**Returns:**
قيمة نصية تمثل حالة الكائن.
