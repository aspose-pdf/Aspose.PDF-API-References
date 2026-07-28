---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Aspose.PDF for Java API Referansı"
description: "RG operatörünü temsil eden sınıf (çizgi operatörleri için RGB rengini ayarlar)."
type: docs
weight: 720
url: /tr/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

RG operatörünü temsil eden sınıf (çizgi operatörleri için RGB rengini ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Operatörü renk ile başlatır. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Yazma programı için yapıcı. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getB](#getB--) | Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi. |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Operatör tarafından belirtilen rengi döndürür. |
| [getG](#getG--) | Yeşil bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında yeşil seviyesi. |
| [getR](#getR--) | Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi. |
| [setB](#setB-double-) | Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi. |
| [setG](#setG-double-) | Yeşil bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında yeşil seviyesi. |
| [setR](#setR-double-) | Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Operatörü renk ile başlatır.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Yazma programı için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r |  | Kırmızı seviyesi 0.0 ile 1.0 arasında |
| g |  | Yeşil seviyesi 0.0 ile 1.0 arasında |
| b |  | Mavi seviyesi 0.0 ile 1.0 arasında |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getB {#getB--}
```
public final double getB()
```

Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi.

**Returns:**
yapılabilir değer

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Operatör tarafından belirtilen rengi döndürür.

**Returns:**
Operatör tarafından belirtilen renk.

### getG {#getG--}
```
public final double getG()
```

Yeşil bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında yeşil seviyesi.

**Returns:**
yapılabilir değer

### getR {#getR--}
```
public final double getR()
```

Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi.

**Returns:**
yapılabilir değer

### setB {#setB-double-}
```
public final void setB(double value)
```

Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |

### setG {#setG-double-}
```
public final void setG(double value)
```

Yeşil bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında yeşil seviyesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |

### setR {#setR-double-}
```
public final void setR(double value)
```

Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |

### toString {#toString--}
```
public String toString()
```

Operatörün metin temsilini döndürür.

**Returns:**
Operatörün metin temsili.
