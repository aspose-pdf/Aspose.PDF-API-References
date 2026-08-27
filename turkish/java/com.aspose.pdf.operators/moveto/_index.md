---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Aspose.PDF for Java API Referansı"
description: "{@code operators.m} operatörünü temsil eden sınıf (taşı ve yeni bir alt yol başlatır)."
type: docs
weight: 410
url: /tr/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

{@code operators.m} operatörünü temsil eden sınıf (taşı ve yeni bir alt yol başlatır).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Yeni {@code Operator.m} (move to) operatörünü başlatır. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getX](#getX--) | X koordinatı |
| [getY](#getY--) | Y koordinatı |
| [setX](#setX-double-) | X koordinatı |
| [setY](#setY-double-) | Y koordinatı |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Yeni {@code Operator.m} (move to) operatörünü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | X koordinatı. |
| y |  | Y koordinatı. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getX {#getX--}
```
public double getX()
```

X koordinatı

**Returns:**
double değer

### getY {#getY--}
```
public double getY()
```

Y koordinatı

**Returns:**
double değer

### setX {#setX-double-}
```
public void setX(double value)
```

X koordinatı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setY {#setY-double-}
```
public void setY(double value)
```

Y koordinatı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toString {#toString--}
```
public String toString()
```

Operatörün metin temsilini döndürür.

**Returns:**
Operatörün metin temsili.
