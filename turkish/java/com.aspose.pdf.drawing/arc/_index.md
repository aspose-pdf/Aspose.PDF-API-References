---
title: "Yay"
linktitle: "Yay"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yayı temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Yayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Arc](#Arc--) | Yalnızca dahili kullanım için |
| [Arc](#Arc-double-double-double-double-double-) | Yeni bir {@code Arc} sınıfı örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getAlpha](#getAlpha--) | Arc'ın başlangıç açı derecesini belirten float değeri alır. |
| [getBeta](#getBeta--) | Arc'ın bitiş açı derecesini belirten float değeri alır. |
| [getPosX](#getPosX--) | Yay merkezinin x-koordinatını gösteren float değeri alır. |
| [getPosY](#getPosY--) | Yay merkezinin y-koordinatını gösteren float değeri alır. |
| [getRadius](#getRadius--) | Arc'ın yarıçapını belirten float değeri alır. |
| [setAlpha](#setAlpha-double-) | Arc'ın başlangıç açı derecesini belirten float değeri ayarlar. |
| [setBeta](#setBeta-double-) | Arc'ın bitiş açı derecesini belirten float değeri ayarlar. |
| [setPosX](#setPosX-double-) | Yay merkezinin x-koordinatını gösteren float değeri ayarlar. |
| [setPosY](#setPosY-double-) | Yay merkezinin y-koordinatını gösteren float değeri ayarlar. |
| [setRadius](#setRadius-double-) | Arc'ın yarıçapını belirten float değeri ayarlar. |

### Arc {#Arc--}
```
public Arc()
```

Yalnızca dahili kullanım için

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Yeni bir {@code Arc} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| posX |  | Arc'ın merkez noktasının x koordinatı. |
| posY |  | Arc'ın merkez noktasının y koordinatı. |
| yarıçap |  | Arc'ın yarıçap değeri. |
| alpha |  | Arc'ın başlangıç açı değeri. |
| beta |  | Arc'ın bitiş açı değeri. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Sığıyorsa true; aksi takdirde false.

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Arc'ın başlangıç açı derecesini belirten float değeri alır.

**Returns:**
alpha değeri.

### getBeta {#getBeta--}
```
public double getBeta()
```

Arc'ın bitiş açı derecesini belirten float değeri alır.

**Returns:**
beta değeri

### getPosX {#getPosX--}
```
public double getPosX()
```

Yay merkezinin x-koordinatını gösteren float değeri alır.

**Returns:**
Yayın merkezinin x-koordinatı.

### getPosY {#getPosY--}
```
public double getPosY()
```

Yay merkezinin y-koordinatını gösteren float değeri alır.

**Returns:**
Yayın merkezinin y-koordinatı.

### getRadius {#getRadius--}
```
public double getRadius()
```

Arc'ın yarıçapını belirten float değeri alır.

**Returns:**
Arc'ın yarıçapını gösteren değer.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Arc'ın başlangıç açı derecesini belirten float değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | alpha değeri. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Arc'ın bitiş açı derecesini belirten float değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | beta değeri |

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Yay merkezinin x-koordinatını gösteren float değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Yayın merkezinin x-koordinatı. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Yay merkezinin y-koordinatını gösteren float değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Yayın merkezinin y-koordinatı. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Arc'ın yarıçapını belirten float değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Arc'ın yarıçapını gösteren. |
