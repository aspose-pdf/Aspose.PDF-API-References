---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Aspose.PDF for Java API Referansı"
description: "d0 operatörünü temsil eden sınıf (glif genişliğini ayarlar)."
type: docs
weight: 510
url: /tr/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

d0 operatörünü temsil eden sınıf (glif genişliğini ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Yapıcı. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getWx](#getWx--) | Glif koordinatının yatay yer değiştirmesi. |
| [getWy](#getWy--) | Glif koordinatının dikey yer değiştirmesi. |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| wx |  | Glifin yatay yer değiştirmesi. |
| wy |  | Glifin dikey yer değiştirmesi. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getWx {#getWx--}
```
public double getWx()
```

Glif koordinatının yatay yer değiştirmesi.

**Returns:**
double değer

### getWy {#getWy--}
```
public double getWy()
```

Glif koordinatının dikey yer değiştirmesi.

**Returns:**
double değer

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
