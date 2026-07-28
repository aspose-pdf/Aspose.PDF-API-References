---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Aspose.PDF for Java API Referansı"
description: "Çizgi işlemleri için gri seviyesini temsil eden sınıf."
type: docs
weight: 650
url: /tr/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Çizgi işlemleri için gri seviyesini temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Operatörü belirtilen renk ile başlatır. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getColor](#getColor--) | Operatör tarafından belirtilen rengi döndürür. |
| [getGray](#getGray--) | Gri değer seviyesini alır veya ayarlar. |
| [setGray](#setGray-double-) | Gri değer seviyesini alır veya ayarlar. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Operatörü belirtilen renk ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gri |  | Gri değer seviyesi. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getColor {#getColor--}
```
public Color getColor()
```

Operatör tarafından belirtilen rengi döndürür.

**Returns:**
Operatör tarafından belirtilen renk.

### getGray {#getGray--}
```
public final double getGray()
```

Gri değer seviyesini alır veya ayarlar.

**Returns:**
double değer

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Gri değer seviyesini alır veya ayarlar.

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
