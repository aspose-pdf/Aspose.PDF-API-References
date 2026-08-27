---
title: "SetGray"
linktitle: "SetGray"
second_title: "Aspose.PDF for Java API Referansı"
description: "Dolgu işlemleri için gri seviyesini ayarla."
type: docs
weight: 640
url: /tr/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Dolgu işlemleri için gri seviyesini ayarla.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetGray](#SetGray-double-) | Yazma programı için yapıcı. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getColor](#getColor--) | Operatör tarafından belirtilen rengi döndürür. |
| [getGray](#getGray--) | Gri değer seviyesini alır veya ayarlar. |
| [setGray](#setGray-double-) | Gri değer seviyesini alır veya ayarlar. |
| [toString](#toString--) | Operatörün string temsilini döndürür. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Yazma programı için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gri |  | Gri değer seviyesi. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
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

Operatörün string temsilini döndürür.

**Returns:**
Operatörün string temsili.
