---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Aspose.PDF for Java API Referansı"
description: "c operatörünü temsil eden sınıf (eğriyi yola ekler)."
type: docs
weight: 150
url: /tr/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

c operatörünü temsil eden sınıf (eğriyi yola ekler).

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [X1](#X1) | X1 koordinatını alır veya ayarlar. |
| [X2](#X2) | X2 koordinatını alır veya ayarlar. |
| [X3](#X3) | X3 koordinatını alır veya ayarlar. |
| [Y1](#Y1) | Y1 koordinatını alır veya ayarlar. |
| [Y2](#Y2) | Y2 koordinatını alır veya ayarlar. |
| [Y3](#Y3) | Y3 koordinatını alır veya ayarlar. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Eğri operatörünü başlatır. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### X1 {#X1}
```
public double X1
```

X1 koordinatını alır veya ayarlar.

### X2 {#X2}
```
public double X2
```

X2 koordinatını alır veya ayarlar.

### X3 {#X3}
```
public double X3
```

X3 koordinatını alır veya ayarlar.

### Y1 {#Y1}
```
public double Y1
```

Y1 koordinatını alır veya ayarlar.

### Y2 {#Y2}
```
public double Y2
```

Y2 koordinatını alır veya ayarlar.

### Y3 {#Y3}
```
public double Y3
```

Y3 koordinatını alır veya ayarlar.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Eğri operatörünü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 |  | İlk noktanın abscisası. |
| y1 |  | İlk noktanın ordinatı. |
| x2 |  | İkinci noktanın abscisası. |
| y2 |  | İkinci noktanın ordinatı. |
| x3 |  | Üçüncü noktanın abscisası. |
| y3 |  | Üçüncü noktanın ordinatı. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Yalnızca dahili kullanım için!

**Returns:**
ICommand değeri ICommand nesnesi

### toString {#toString--}
```
public String toString()
```

Operatörün metin temsilini döndürür.

**Returns:**
Operatörün metin temsili.
