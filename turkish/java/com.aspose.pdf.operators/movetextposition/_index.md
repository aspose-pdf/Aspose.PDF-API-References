---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Aspose.PDF for Java API Referansı"
description: "Td operatörünü temsil eden sınıf (metin konumunu taşır)."
type: docs
weight: 390
url: /tr/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Td operatörünü temsil eden sınıf (metin konumunu taşır).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Operatörü başlatır. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Operatörü başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getX](#getX--) | Metin konumunun X koordinatı. |
| [getY](#getY--) | Metin konumunun Y koordinatı. |
| [setX](#setX-double-) | Metin konumunun X koordinatı. |
| [setY](#setY-double-) | Metin konumunun Y koordinatı. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Operatörü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | Metin konumunun X koordinatı. |
| y |  | Metin konumunun Y koordinatı. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Operatörü başlatır.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getX {#getX--}
```
public double getX()
```

Metin konumunun X koordinatı.

**Returns:**
double değer

### getY {#getY--}
```
public double getY()
```

Metin konumunun Y koordinatı.

**Returns:**
double değer

### setX {#setX-double-}
```
public void setX(double value)
```

Metin konumunun X koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setY {#setY-double-}
```
public void setY(double value)
```

Metin konumunun Y koordinatı.

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
