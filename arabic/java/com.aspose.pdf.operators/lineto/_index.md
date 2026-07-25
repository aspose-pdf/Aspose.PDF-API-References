---
title: "LineTo"
linktitle: "LineTo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل l (إضافة خط إلى المسار)."
type: docs
weight: 380
url: /ar/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

فئة تمثّل عامل l (إضافة خط إلى المسار).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LineTo](#LineTo-double-double-) | يُهيئ معامل الخط. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getX](#getX--) | الإحداثي X لنقطة الخط. |
| [getY](#getY--) | الإحداثي Y لنقطة الخط. |
| [setX](#setX-double-) | الإحداثي X لنقطة الخط. |
| [setY](#setY-double-) | الإحداثي Y لنقطة الخط. |
| [toString](#toString--) | يعيد تمثيل النص للمشغل. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

يُهيئ معامل الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | إحداثي X. |
| y |  | إحداثي Y. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getX {#getX--}
```
public double getX()
```

الإحداثي X لنقطة الخط.

**Returns:**
قيمة double

### getY {#getY--}
```
public double getY()
```

الإحداثي Y لنقطة الخط.

**Returns:**
قيمة double

### setX {#setX-double-}
```
public void setX(double value)
```

الإحداثي X لنقطة الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setY {#setY-double-}
```
public void setY(double value)
```

الإحداثي Y لنقطة الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toString {#toString--}
```
public String toString()
```

يعيد تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
