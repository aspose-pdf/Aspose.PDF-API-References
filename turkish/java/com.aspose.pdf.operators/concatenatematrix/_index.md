---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Aspose.PDF for Java API Referansı"
description: "cm operatörünü temsil eden sınıf (matrisi mevcut dönüşüm matrisine ekler)."
type: docs
weight: 140
url: /tr/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

cm operatörünü temsil eden sınıf (matrisi mevcut dönüşüm matrisine ekler).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Operatör sınıfı için yapıcı. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Operatör sınıfı için yapıcı. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Operatörü matrisle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getMatrix](#getMatrix--) | Operatörün matris argümanı. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Operatörün matris argümanı. |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Operatör sınıfı için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a |  | A katsayısı |
| b |  | B katsayısı |
| c |  | C katsayısı |
| d |  | D katsayısı |
| e |  | E katsayısı |
| f |  | F katsayısı |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Operatör sınıfı için yapıcı.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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
Temsilin metin temsili
