---
title: "LineTo"
linktitle: "LineTo"
second_title: "Aspose.PDF for Java API Referansı"
description: "l operatörünü temsil eden sınıf (yola bir çizgi ekler)."
type: docs
weight: 380
url: /tr/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

l operatörünü temsil eden sınıf (yola bir çizgi ekler).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Satır operatörünü başlatır. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getX](#getX--) | Satır noktasının X koordinatı. |
| [getY](#getY--) | Çizgi noktasının Y koordinatı. |
| [setX](#setX-double-) | Satır noktasının X koordinatı. |
| [setY](#setY-double-) | Çizgi noktasının Y koordinatı. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Satır operatörünü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | X koordinatı. |
| y |  | Y koordinatı. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getX {#getX--}
```
public double getX()
```

Satır noktasının X koordinatı.

**Returns:**
double değer

### getY {#getY--}
```
public double getY()
```

Çizgi noktasının Y koordinatı.

**Returns:**
double değer

### setX {#setX-double-}
```
public void setX(double value)
```

Satır noktasının X koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setY {#setY-double-}
```
public void setY(double value)
```

Çizgi noktasının Y koordinatı.

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
