---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Aspose.PDF for Java API Referansı"
description: "i operatörünü temsil eden sınıf (düzlük toleransını ayarlar)."
type: docs
weight: 620
url: /tr/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

i operatörünü temsil eden sınıf (düzlük toleransını ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Operatörü başlatır. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için bir ziyaretçi nesnesi kabul eder. |
| [getFlatness](#getFlatness--) | Düzlüğü alır. |
| [setFlatness](#setFlatness-double-) | Düzlüğü ayarlar. |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Operatörü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| düzlük |  | Düzlüğün değeri. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için bir ziyaretçi nesnesi kabul eder.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Düzlüğü alır.

**Returns:**
double değer

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Düzlüğü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Yalnızca dahili kullanım için!

**Returns:**
ICommand değeri ICommand nesnesi
