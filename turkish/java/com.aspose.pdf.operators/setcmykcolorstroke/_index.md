---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Aspose.PDF for Java API Referansı"
description: "K operatörünü temsil eden sınıf (çizim işlemleri için CMYK rengi ayarlar)."
type: docs
weight: 540
url: /tr/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

K operatörünü temsil eden sınıf (çizim işlemleri için CMYK rengi ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Operatörü başlatır. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getC](#getC--) | Camgöbeği bileşenini alır veya ayarlar. |
| [getColor](#getColor--) | RGB rengini döndürür |
| [getK](#getK--) | Siyah bileşeni alır veya ayarlar. |
| [getM](#getM--) | Macenta bileşenini alır veya ayarlar. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Sarı bileşeni alır veya ayarlar. |
| [setC](#setC-double-) | Camgöbeği bileşenini alır veya ayarlar. |
| [setK](#setK-double-) | Siyah bileşeni alır veya ayarlar. |
| [setM](#setM-double-) | Macenta bileşenini alır veya ayarlar. |
| [setY](#setY-double-) | Sarı bileşeni alır veya ayarlar. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Operatörü başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c |  | Siyan seviyesini 0.0 ile 1.0 arasında |
| m |  | Macenta seviyesini 0.0 ile 1.0 arasında |
| y |  | Sarı seviyesini 0.0 ile 1.0 arasında |
| k |  | Siyah seviyesini 0.0 ile 1.0 arasında |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getC {#getC--}
```
public final double getC()
```

Camgöbeği bileşenini alır veya ayarlar.

**Returns:**
yapılabilir değer

### getColor {#getColor--}
```
public Color getColor()
```

RGB rengini döndürür

**Returns:**
Operatör tarafından belirtilen renk.

### getK {#getK--}
```
public final double getK()
```

Siyah bileşeni alır veya ayarlar.

**Returns:**
yapılabilir değer

### getM {#getM--}
```
public final double getM()
```

Macenta bileşenini alır veya ayarlar.

**Returns:**
yapılabilir değer

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Sarı bileşeni alır veya ayarlar.

**Returns:**
yapılabilir değer

### setC {#setC-double-}
```
public final void setC(double value)
```

Camgöbeği bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |

### setK {#setK-double-}
```
public final void setK(double value)
```

Siyah bileşeni alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |

### setM {#setM-double-}
```
public final void setM(double value)
```

Macenta bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |

### setY {#setY-double-}
```
public final void setY(double value)
```

Sarı bileşeni alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yapılabilir değer |
