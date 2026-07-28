---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Aspose.PDF for Java API Referansı"
description: "SC operatörünü temsil eden sınıf (çizgi renk operatörleri için rengi ayarlar)."
type: docs
weight: 600
url: /tr/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

SC operatörünü temsil eden sınıf (çizgi renk operatörleri için rengi ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Operatörü başlatır. |
| [SetColorStroke](#SetColorStroke-double-) | DeviceGray, CalGray ve Indexed renk uzayları için strokleme operatörlerinin rengini ayarlayın. |
| [SetColorStroke](#SetColorStroke-double:A-) | Renk bileşenlerini ayarlamaya izin veren yapıcı. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | DeviceRGB, CalRGB ve Lab renk uzayları için strokleme operatörünün rengini ayarlayın. |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | CMYK renk uzayı için strokleme operatörünün rengini ayarlayın. |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Operatörü başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getB](#getB--) | Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi. |
| [getC](#getC--) | Camgöbeği bileşenini alır veya ayarlar. |
| [getColor](#getColor--) | Operatör tarafından belirtilen rengi döndürür. |
| [getG](#getG--) | Yeşil bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında yeşil seviyesi. |
| [getK](#getK--) | Siyah bileşeni alır veya ayarlar. |
| [getM](#getM--) | Macenta bileşenini alır veya ayarlar. |
| [getR](#getR--) | Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi. |
| [getY](#getY--) | Sarı bileşeni alır veya ayarlar. |
| [setB](#setB-double-) | Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi. |
| [setC](#setC-double-) | Camgöbeği bileşenini alır veya ayarlar. |
| [setG](#setG-double-) | Yeşil bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında yeşil seviyesi. |
| [setK](#setK-double-) | Siyah bileşeni alır veya ayarlar. |
| [setM](#setM-double-) | Macenta bileşenini alır veya ayarlar. |
| [setR](#setR-double-) | Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi. |
| [setY](#setY-double-) | Sarı bileşeni alır veya ayarlar. |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Operatörü başlatır.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

DeviceGray, CalGray ve Indexed renk uzayları için strokleme operatörlerinin rengini ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g |  | Renk değeri. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Renk bileşenlerini ayarlamaya izin veren yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renk |  | Renk bileşenlerinin dizisi. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

DeviceRGB, CalRGB ve Lab renk uzayları için strokleme operatörünün rengini ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r |  | Kırmızı bileşen. |
| g |  | Yeşil bileşen. |
| b |  | Mavi bileşen. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

CMYK renk uzayı için strokleme operatörünün rengini ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c |  | Camgöbeği bileşen. |
| m |  | Macenta bileşen. |
| y |  | Sarı bileşen. |
| k |  | Siyah bileşen. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
Operatörü başlatır.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getB {#getB--}
```
public final double getB()
```

Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi.

**Returns:**
yapılabilir değer

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

### getR {#getR--}
```
public final double getR()
```

Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi.

**Returns:**
yapılabilir değer

### getY {#getY--}
```
public final double getY()
```

Sarı bileşeni alır veya ayarlar.

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

### setC {#setC-double-}
```
public final void setC(double value)
```

Camgöbeği bileşenini alır veya ayarlar.

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
| değer |  | double değer |

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

### setR {#setR-double-}
```
public final void setR(double value)
```

Kırmızı bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında kırmızı seviyesi.

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
