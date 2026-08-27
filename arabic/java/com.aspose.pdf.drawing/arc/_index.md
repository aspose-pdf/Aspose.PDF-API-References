---
title: "قوس"
linktitle: "قوس"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل قوسًا."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

يمثل قوسًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Arc](#Arc--) | للاستخدام الداخلي فقط |
| [Arc](#Arc-double-double-double-double-double-) | يقوم بإنشاء نسخة جديدة من الفئة {@code Arc}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | يتحقق مما إذا كان العنصر يتناسب مع أبعاد الحاوية المحددة (شاملاً). |
| [getAlpha](#getAlpha--) | يحصل على قيمة عائمة تشير إلى درجة زاوية البداية للقوس. |
| [getBeta](#getBeta--) | يحصل على قيمة عائمة تشير إلى درجة زاوية النهاية للقوس. |
| [getPosX](#getPosX--) | يحصل على قيمة عائمة تشير إلى الإحداثي السيني لمركز القوس. |
| [getPosY](#getPosY--) | يحصل على قيمة عائمة تشير إلى الإحداثي الصادي لمركز القوس. |
| [getRadius](#getRadius--) | يحصل على قيمة عائمة تشير إلى نصف قطر القوس. |
| [setAlpha](#setAlpha-double-) | يضبط قيمة عائمة تشير إلى درجة زاوية البداية للقوس. |
| [setBeta](#setBeta-double-) | يضبط قيمة عائمة تشير إلى درجة زاوية النهاية للقوس. |
| [setPosX](#setPosX-double-) | يضبط قيمة عائمة تشير إلى الإحداثي السيني لمركز القوس. |
| [setPosY](#setPosY-double-) | يضبط قيمة عائمة تشير إلى الإحداثي الصادي لمركز القوس. |
| [setRadius](#setRadius-double-) | يضبط قيمة عائمة تشير إلى نصف قطر القوس. |

### Arc {#Arc--}
```
public Arc()
```

للاستخدام الداخلي فقط

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

يقوم بإنشاء نسخة جديدة من الفئة {@code Arc}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| posX |  | الإحداثي السيني لنقطة مركز القوس. |
| posY |  | الإحداثي الصادي لنقطة مركز القوس. |
| نصف القطر |  | قيمة نصف قطر القوس. |
| alpha |  | قيمة زاوية البداية للقوس. |
| beta |  | قيمة زاوية النهاية للقوس. |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

يحصل على قيمة عائمة تشير إلى درجة زاوية البداية للقوس.

**Returns:**
قيمة alpha.

### getBeta {#getBeta--}
```
public double getBeta()
```

يحصل على قيمة عائمة تشير إلى درجة زاوية النهاية للقوس.

**Returns:**
قيمة beta

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

يحصل على قيمة عائمة تشير إلى نصف قطر القوس.

**Returns:**
قيمة تشير إلى نصف قطر القوس.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

يضبط قيمة عائمة تشير إلى درجة زاوية البداية للقوس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة alpha. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

يضبط قيمة عائمة تشير إلى درجة زاوية النهاية للقوس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة beta |

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

يضبط قيمة عائمة تشير إلى نصف قطر القوس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | تشير إلى نصف قطر القوس. |
