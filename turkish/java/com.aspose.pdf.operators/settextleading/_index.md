---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Aspose.PDF for Java API Referansı"
description: "TL operatörünü temsil eden sınıf (metin satır aralığını ayarlar)."
type: docs
weight: 740
url: /tr/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

TL operatörünü temsil eden sınıf (metin satır aralığını ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Metin satır aralığı operatörü için yapıcı. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getLeading](#getLeading--) | Metin satır aralığını alır. |
| [setLeading](#setLeading-double-) | Metin satır aralığını ayarlar. |
| [toString](#toString--) | Operatörün metin kodunu üretir. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Metin satır aralığı operatörü için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leading |  | Metin satır aralığı. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getLeading {#getLeading--}
```
public double getLeading()
```

Metin satır aralığını alır.

**Returns:**
double değer

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Metin satır aralığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toString {#toString--}
```
public String toString()
```

Operatörün metin kodunu üretir.

**Returns:**
Operatörün metin temsili.
