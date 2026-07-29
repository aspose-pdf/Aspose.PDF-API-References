---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل Td (تحريك موضع النص)."
type: docs
weight: 390
url: /ar/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

فئة تمثّل عامل Td (تحريك موضع النص).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | يقوم بتهيئة المشغل. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | يقوم بتهيئة المشغل. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getX](#getX--) | الإحداثي X لموضع النص. |
| [getY](#getY--) | الإحداثي Y لموضع النص. |
| [setX](#setX-double-) | الإحداثي X لموضع النص. |
| [setY](#setY-double-) | الإحداثي Y لموضع النص. |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

يقوم بتهيئة المشغل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | الإحداثي X لموضع النص. |
| y |  | الإحداثي Y لموضع النص. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
يقوم بتهيئة المشغل.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getX {#getX--}
```
public double getX()
```

الإحداثي X لموضع النص.

**Returns:**
قيمة double

### getY {#getY--}
```
public double getY()
```

الإحداثي Y لموضع النص.

**Returns:**
قيمة double

### setX {#setX-double-}
```
public void setX(double value)
```

الإحداثي X لموضع النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setY {#setY-double-}
```
public void setY(double value)
```

الإحداثي Y لموضع النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toString {#toString--}
```
public String toString()
```

يرجع تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
