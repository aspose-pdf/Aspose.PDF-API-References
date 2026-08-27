---
title: "نقطة"
linktitle: "نقطة"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل نقطة ذات إحداثيات كسرية."
type: docs
weight: 3870
url: /ar/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

يمثل نقطة ذات إحداثيات كسرية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Point](#Point-double-double-) | يُنشئ مثلاً جديداً من {@code Point}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | يحسب المسافة بين نقطتين. |
| [getTrivial](#getTrivial--) | يحصل على نقطة ذات إحداثيات صفرية. |
| [getX](#getX--) | يحصل على قيمة إحداثي X. |
| [getY](#getY--) | يحصل على قيمة إحداثي Y. |
| [setX](#setX-double-) | يضبط قيمة إحداثي X. |
| [setY](#setY-double-) | يضبط قيمة إحداثي Y. |
| [toPoint](#toPoint--) | يحوّل النقطة إلى كائن java.awt.geom.Point2D.Float. |
| [toString](#toString--) | إرجاع تمثيل السلسلة للنقطة الحالية. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

يُنشئ مثلاً جديداً من {@code Point}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | قيمة إحداثي x. |
| y |  | قيمة إحداثي y. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
يحسب المسافة بين نقطتين.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

يحصل على نقطة ذات إحداثيات صفرية.

**Returns:**
كائن Point

### getX {#getX--}
```
public double getX()
```

يحصل على قيمة إحداثي X.

**Returns:**
قيمة double

### getY {#getY--}
```
public double getY()
```

يحصل على قيمة إحداثي Y.

**Returns:**
قيمة double

### setX {#setX-double-}
```
public void setX(double value)
```

يضبط قيمة إحداثي X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setY {#setY-double-}
```
public void setY(double value)
```

يضبط قيمة إحداثي Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

يحوّل النقطة إلى كائن java.awt.geom.Point2D.Float.

**Returns:**
بنية Float.

### toString {#toString--}
```
public String toString()
```

إرجاع تمثيل السلسلة للنقطة الحالية.

**Returns:**
سلسلة تمثل النقطة الحالية.
