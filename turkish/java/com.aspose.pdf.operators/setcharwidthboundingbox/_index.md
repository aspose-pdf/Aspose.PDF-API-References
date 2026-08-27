---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Aspose.PDF for Java API Referansı"
description: "d1 operatörünü temsil eden sınıf (glifi ve sınırlama kutusunu ayarlar)."
type: docs
weight: 520
url: /tr/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

d1 operatörünü temsil eden sınıf (glifi ve sınırlama kutusunu ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | SetCharWidthBoundingBox operatörünü başlatır. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getLlx](#getLlx--) | Sınırlayıcı dikdörtgenin sol-alt yatay koordinatı. |
| [getLly](#getLly--) | Sınırlayıcı dikdörtgenin sol-alt dikey koordinatı. |
| [getUrx](#getUrx--) | Sınırlayıcı dikdörtgenin sağ-üst yatay koordinatı. |
| [getUry](#getUry--) | Sınırlayıcı dikdörtgenin sağ-üst dikey koordinatı. |
| [getWx](#getWx--) | Glifin yatay yer değiştirmesi. |
| [getWy](#getWy--) | Glifin dikey yer değiştirmesi. |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

SetCharWidthBoundingBox operatörünü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| wx |  | Glif koordinatındaki yatay yer değiştirmeyi gösterir. |
| wy |  | Glif koordinatındaki dikey yer değiştirmeyi gösterir. 0 olmalıdır. |
| llx |  | Sol-alt köşenin X koordinatını gösterir. |
| lly |  | Sol-alt köşenin Y koordinatını gösterir. |
| urx |  | Sağ-üst köşenin X koordinatını gösterir. |
| ury |  | Sağ-üst köşenin Y koordinatını gösterir. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getLlx {#getLlx--}
```
public double getLlx()
```

Sınırlayıcı dikdörtgenin sol-alt yatay koordinatı.

**Returns:**
double değer

### getLly {#getLly--}
```
public double getLly()
```

Sınırlayıcı dikdörtgenin sol-alt dikey koordinatı.

**Returns:**
double değer

### getUrx {#getUrx--}
```
public double getUrx()
```

Sınırlayıcı dikdörtgenin sağ-üst yatay koordinatı.

**Returns:**
double değer

### getUry {#getUry--}
```
public double getUry()
```

Sınırlayıcı dikdörtgenin sağ-üst dikey koordinatı.

**Returns:**
double değer

### getWx {#getWx--}
```
public double getWx()
```

Glifin yatay yer değiştirmesi.

**Returns:**
double değer

### getWy {#getWy--}
```
public double getWy()
```

Glifin dikey yer değiştirmesi.

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
