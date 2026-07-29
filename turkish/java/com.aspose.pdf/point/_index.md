---
title: "Nokta"
linktitle: "Nokta"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kesirli koordinatlara sahip bir noktayı temsil eder."
type: docs
weight: 3870
url: /tr/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Kesirli koordinatlara sahip bir noktayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Point](#Point-double-double-) | Yeni {@code Point} örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | İki nokta arasındaki mesafeyi hesaplar. |
| [getTrivial](#getTrivial--) | Sıfır koordinatlı noktayı alır. |
| [getX](#getX--) | X koordinat değerini al. |
| [getY](#getY--) | Y koordinat değerini al. |
| [setX](#setX-double-) | X koordinat değerini ayarlar. |
| [setY](#setY-double-) | Y koordinat değerini ayarlar. |
| [toPoint](#toPoint--) | Noktayı java.awt.geom.Point2D.Float nesnesine dönüştürür. |
| [toString](#toString--) | Geçerli noktanın dize temsilini döndürür. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Yeni {@code Point} örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | x koordinat değeri. |
| y |  | y koordinat değeri. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
İki nokta arasındaki mesafeyi hesaplar.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Sıfır koordinatlı noktayı alır.

**Returns:**
Nokta nesnesi

### getX {#getX--}
```
public double getX()
```

X koordinat değerini al.

**Returns:**
double değer

### getY {#getY--}
```
public double getY()
```

Y koordinat değerini al.

**Returns:**
double değer

### setX {#setX-double-}
```
public void setX(double value)
```

X koordinat değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setY {#setY-double-}
```
public void setY(double value)
```

Y koordinat değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Noktayı java.awt.geom.Point2D.Float nesnesine dönüştürür.

**Returns:**
Float yapısı.

### toString {#toString--}
```
public String toString()
```

Geçerli noktanın dize temsilini döndürür.

**Returns:**
Geçerli noktayı temsil eden dize.
