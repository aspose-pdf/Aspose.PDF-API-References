---
title: "SetColor"
linktitle: "SetColor"
second_title: "Aspose.PDF for Java API Referansı"
description: "sc operatörü için sınıfı temsil eder (çizim dışı işlemler için rengi ayarlar)."
type: docs
weight: 550
url: /tr/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

sc operatörü için sınıfı temsil eder (çizim dışı işlemler için rengi ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetColor](#SetColor--) | Operatörü başlatır. |
| [SetColor](#SetColor-double-) | DeviceGray, CalGray ve Indexed renk uzayları için strokleme operatörlerinin rengini ayarlayın. |
| [SetColor](#SetColor-double:A-) | Renk bileşenlerini belirtmeye izin veren yapıcı. |
| [SetColor](#SetColor-double-double-double-) | DeviceRGB, CalRGB ve Lab renk uzayları için strokleme operatörünün rengini ayarlayın. |
| [SetColor](#SetColor-double-double-double-double-) | CMYK renk uzayı için çizim yapmayan operatörün rengini ayarla |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | Operatörü başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getB](#getB--) | Mavi bileşeni alır veya ayarlar. Değer: 0.0 ile 1.0 arasında mavi seviyesi. |
| [getC](#getC--) | Camgöbeği bileşenini alır veya ayarlar. |
| [getColor](#getColor--) | Henüz desteklenmiyor. Operatör tarafından belirtilen rengi döndürür. |
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
| [toString](#toString--) | Rengin dize temsili döndürülür. |

### SetColor {#SetColor--}
```
public SetColor()
```

Operatörü başlatır.

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

DeviceGray, CalGray ve Indexed renk uzayları için strokleme operatörlerinin rengini ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g |  | Renk değeri. |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

Renk bileşenlerini belirtmeye izin veren yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renk |  | Renk bileşenlerinin dizisi. |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

DeviceRGB, CalRGB ve Lab renk uzayları için strokleme operatörünün rengini ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r |  | Kırmızı bileşen. |
| g |  | Yeşil bileşen. |
| b |  | Mavi bileşen. |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

CMYK renk uzayı için çizim yapmayan operatörün rengini ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c |  | Camgöbeği bileşen. |
| m |  | Macenta bileşen. |
| y |  | Sarı bileşen. |
| k |  | Siyah bileşen. |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
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

Henüz desteklenmiyor. Operatör tarafından belirtilen rengi döndürür.

**Returns:**
Operatör rengi.

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

### toString {#toString--}
```
public String toString()
```

Rengin dize temsili döndürülür.

**Returns:**
Rengin dize temsili.
