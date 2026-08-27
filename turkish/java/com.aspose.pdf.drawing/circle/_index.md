---
title: "Daire"
linktitle: "Daire"
second_title: "Aspose.PDF for Java API Referansı"
description: "Dairayı temsil eder."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Dairayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Circle](#Circle--) | Yalnızca dahili kullanım için |
| [Circle](#Circle-float-float-float-) | Yeni bir {@code Circle} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getPosX](#getPosX--) | Yay merkezinin x-koordinatını gösteren float değeri alır. |
| [getPosY](#getPosY--) | Yay merkezinin y-koordinatını gösteren float değeri alır. |
| [getRadius](#getRadius--) | Dairenin yarıçapını gösteren float değeri alır. |
| [setPosX](#setPosX-double-) | Yay merkezinin x-koordinatını gösteren float değeri ayarlar. |
| [setPosY](#setPosY-double-) | Yay merkezinin y-koordinatını gösteren float değeri ayarlar. |
| [setRadius](#setRadius-double-) | Dairenin yarıçapını gösteren float değeri ayarlar. |

### Circle {#Circle--}
```
public Circle()
```

Yalnızca dahili kullanım için

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Yeni bir {@code Circle} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| posX |  | Dairenin merkezinin x-koordinatı. |
| posY |  | Dairenin merkezinin y-koordinatı. |
| yarıçap |  | Dairenin yarıçapı. |

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

Dairenin yarıçapını gösteren float değeri alır.

**Returns:**
dairenin yarıçapını gösteren değer.

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

Dairenin yarıçapını gösteren float değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dairenin yarıçapını gösterir. |
