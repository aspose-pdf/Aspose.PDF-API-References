---
title: "Re"
linktitle: "Re"
second_title: "Aspose.PDF for Java API Referansı"
description: "re operatörünü temsil eden sınıf (yola bir dikdörtgen ekler)."
type: docs
weight: 460
url: /tr/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

re operatörünü temsil eden sınıf (yola bir dikdörtgen ekler).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Re](#Re--) | Hedefleri çıkarmak için yapıcı. |
| [Re](#Re-double-double-double-double-) | Yazma programı için yapıcı. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Hedefleri çıkarmak için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getHeight](#getHeight--) | Dikdörtgenin yüksekliği. |
| [getWidth](#getWidth--) | Dikdörtgenin genişliğini alır. |
| [getX](#getX--) | Dikdörtgenin en sol yanının X koordinatı. |
| [getY](#getY--) | Dikdörtgenin alt yanının Y koordinatı. |
| [setHeight](#setHeight-double-) | Dikdörtgenin yüksekliği. |
| [setWidth](#setWidth-double-) | Dikdörtgenin genişliğini ayarlar. |
| [setX](#setX-double-) | Dikdörtgenin en sol yanının X koordinatı. |
| [setY](#setY-double-) | Dikdörtgenin alt yanının Y koordinatı. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### Re {#Re--}
```
public Re()
```

Hedefleri çıkarmak için yapıcı.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Yazma programı için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | Dikdörtgenin sol-alt köşesinin X koordinatı. |
| y |  | Dikdörtgenin sol-alt köşesinin Y koordinatı. |
| genişlik |  | Dikdörtgenin genişliği. |
| yükseklik |  | Dikdörtgenin yüksekliği. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Hedefleri çıkarmak için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getHeight {#getHeight--}
```
public double getHeight()
```

Dikdörtgenin yüksekliği.

**Returns:**
Dikdörtgenin yüksekliği.

### getWidth {#getWidth--}
```
public double getWidth()
```

Dikdörtgenin genişliğini alır.

**Returns:**
dikdörtgenin genişliği.

### getX {#getX--}
```
public double getX()
```

Dikdörtgenin en sol yanının X koordinatı.

**Returns:**
double değer

### getY {#getY--}
```
public double getY()
```

Dikdörtgenin alt yanının Y koordinatı.

**Returns:**
double değer

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Dikdörtgenin yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Dikdörtgenin yüksekliği. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Dikdörtgenin genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dikdörtgenin genişliği. |

### setX {#setX-double-}
```
public void setX(double value)
```

Dikdörtgenin en sol yanının X koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setY {#setY-double-}
```
public void setY(double value)
```

Dikdörtgenin alt yanının Y koordinatı.

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
