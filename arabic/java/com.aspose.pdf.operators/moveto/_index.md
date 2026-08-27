---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل {@code operators.m} (التحرك إلى وبدء مسار فرعي جديد)."
type: docs
weight: 410
url: /ar/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

فئة تمثّل {@code operators.m} (التحرك إلى وبدء مسار فرعي جديد).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | يُهيئ مشغل {@code Operator.m} (move to) جديد. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getX](#getX--) | الإحداثي X |
| [getY](#getY--) | الإحداثي Y |
| [setX](#setX-double-) | الإحداثي X |
| [setY](#setY-double-) | الإحداثي Y |
| [toString](#toString--) | يعيد تمثيل النص للمشغل. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

يُهيئ مشغل {@code Operator.m} (move to) جديد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | الإحداثي X. |
| y |  | الإحداثي Y. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getX {#getX--}
```
public double getX()
```

الإحداثي X

**Returns:**
قيمة double

### getY {#getY--}
```
public double getY()
```

الإحداثي Y

**Returns:**
قيمة double

### setX {#setX-double-}
```
public void setX(double value)
```

الإحداثي X

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setY {#setY-double-}
```
public void setY(double value)
```

الإحداثي Y

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
