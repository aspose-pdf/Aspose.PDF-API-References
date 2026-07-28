---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Aspose.PDF for Java API Referansı"
description: "Tm operatörünü temsil eden sınıf (metin matrisini ayarlar)."
type: docs
weight: 750
url: /tr/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Tm operatörünü temsil eden sınıf (metin matrisini ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Operatörü başlatır. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Operatörü başlatır. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Operatörü matrisle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getMatrix](#getMatrix--) | Operatörün matris argümanı. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Operatörün matris argümanı. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Operatörü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a |  | A katsayısı |
| b |  | B katsayısı |
| c |  | C katsayısı |
| d |  | D katsayısı |
| e |  | E katsayısı |
| f |  | F katsayısı |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Operatörü başlatır.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Operatörü matrisle başlatır.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Operatörün matris argümanı.

**Returns:**
Matrix nesnesi

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Operatörün matris argümanı.

### toString {#toString--}
```
public String toString()
```

Operatörün metin temsilini döndürür.

**Returns:**
Operatörün metin temsili.
