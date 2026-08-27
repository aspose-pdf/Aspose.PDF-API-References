---
title: "دائرة"
linktitle: "دائرة"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل دائرة."
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

يمثل دائرة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Circle](#Circle--) | للاستخدام الداخلي فقط |
| [Circle](#Circle-float-float-float-) | يُنشئ مثيلاً جديداً للفئة {@code Circle}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً). |
| [getPosX](#getPosX--) | يحصل على قيمة عائمة تشير إلى الإحداثي السيني لمركز القوس. |
| [getPosY](#getPosY--) | يحصل على قيمة عائمة تشير إلى الإحداثي الصادي لمركز القوس. |
| [getRadius](#getRadius--) | يحصل على قيمة عائمة تشير إلى نصف قطر الدائرة. |
| [setPosX](#setPosX-double-) | يضبط قيمة عائمة تشير إلى الإحداثي السيني لمركز القوس. |
| [setPosY](#setPosY-double-) | يضبط قيمة عائمة تشير إلى الإحداثي الصادي لمركز القوس. |
| [setRadius](#setRadius-double-) | يضبط قيمة عائمة تشير إلى نصف قطر الدائرة. |

### Circle {#Circle--}
```
public Circle()
```

للاستخدام الداخلي فقط

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

يُنشئ مثيلاً جديداً للفئة {@code Circle}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| posX |  | الإحداثي السيني لمركز الدائرة. |
| posY |  | الإحداثي الصادي لمركز الدائرة. |
| نصف القطر |  | نصف قطر الدائرة. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
صحيح إذا كان يتناسب؛ وإلا، خطأ.

### getPosX {#getPosX--}
```
public double getPosX()
```

يحصل على قيمة عائمة تشير إلى الإحداثي السيني لمركز القوس.

**Returns:**
الإحداثي السيني لمركز القوس.

### getPosY {#getPosY--}
```
public double getPosY()
```

يحصل على قيمة عائمة تشير إلى الإحداثي الصادي لمركز القوس.

**Returns:**
الإحداثي الصادي لمركز القوس.

### getRadius {#getRadius--}
```
public double getRadius()
```

يحصل على قيمة عائمة تشير إلى نصف قطر الدائرة.

**Returns:**
قيمة تشير إلى نصف قطر الدائرة.

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

يضبط قيمة عائمة تشير إلى الإحداثي السيني لمركز القوس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الإحداثي السيني لمركز القوس. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

يضبط قيمة عائمة تشير إلى الإحداثي الصادي لمركز القوس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الإحداثي الصادي لمركز القوس. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

يضبط قيمة عائمة تشير إلى نصف قطر الدائرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | تشير إلى نصف قطر الدائرة. |
