---
title: "GraphInfo"
linktitle: "GraphInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل معلومات الرسومات."
type: docs
weight: 1840
url: /ar/java/com.aspose.pdf/graphinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.GraphInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class GraphInfo extends Object implements com.aspose.ms.System.ICloneable
```

يمثل معلومات الرسومات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GraphInfo](#GraphInfo--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | استنساخ معلومات الرسومات. |
| [getColor](#getColor--) | يحصل على كائن {@code Color} الذي يشير إلى لون الرسم البياني. |
| [getDashArray](#getDashArray--) | يحصل على مصفوفة الشرط. |
| [getDashPhase](#getDashPhase--) | يحصل على مرحلة الشرط. |
| [getFillColor](#getFillColor--) | يحصل على كائن {@code Color} الذي يشير إلى لون التعبئة للرسم البياني. |
| [getLineWidth](#getLineWidth--) | يحصل على قيمة عائمة تشير إلى عرض الخط للرسم البياني. |
| [getRotationAngle](#getRotationAngle--) | يحصل على قيمة عائمة تشير إلى زاوية الدوران لنظام الإحداثيات عند تحويل نظام الإحداثيات. |
| [getScalingRateX](#getScalingRateX--) | يحصل على قيمة عائمة تشير إلى معدل التحجيم للإحداثي x عند تحويل نظام الإحداثيات. |
| [getScalingRateY](#getScalingRateY--) | يحصل على قيمة عائمة تشير إلى معدل التحجيم للإحداثي y عند تحويل نظام الإحداثيات. |
| [getSkewAngleX](#getSkewAngleX--) | يحصل على قيمة عائمة تشير إلى زاوية الانحراف للإحداثي x عند تحويل نظام الإحداثيات. |
| [getSkewAngleY](#getSkewAngleY--) | يحصل على قيمة عائمة تشير إلى زاوية الانحراف للإحداثي y عند تحويل نظام الإحداثيات. |
| [getX](#getX--) | استرجع إحداثي X للحد العمودي عند استخدام TableAbsorber، وأرجع "-1" للحد الأفقي. |
| [getY](#getY--) | استرجع إحداثي Y للحد الأفقي عند استخدام TableAbsorber، وأرجع "-1" للحد العمودي. |
| [isDoubled](#isDoubled--) | يحصل على ما إذا كان الحد مزدوجًا. |
| [setColor](#setColor-com.aspose.pdf.Color-) | يضبط كائن {@code Color} الذي يشير إلى لون الرسم البياني. |
| [setDashArray](#setDashArray-int:A-) | يضبط مصفوفة الفواصل. |
| [setDashPhase](#setDashPhase-int-) | يضبط مرحلة الفواصل. |
| [setDoubled](#setDoubled-boolean-) | يضبط ما إذا كان الحد مزدوجًا. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | يضبط كائن {@code Color} الذي يشير إلى لون التعبئة للرسم البياني. |
| [setLineWidth](#setLineWidth-float-) | يضبط قيمة عائمة تشير إلى عرض الخط للرسم البياني. |
| [setRotationAngle](#setRotationAngle-double-) | يضبط قيمة عائمة تشير إلى زاوية دوران نظام الإحداثيات عند تحويل نظام الإحداثيات. |
| [setScalingRateX](#setScalingRateX-double-) | يضبط قيمة عائمة تشير إلى معدل التحجيم للإحداثي x عند تحويل نظام الإحداثيات. |
| [setScalingRateY](#setScalingRateY-double-) | يضبط قيمة عائمة تشير إلى معدل التحجيم للإحداثي y عند تحويل نظام الإحداثيات. |
| [setSkewAngleX](#setSkewAngleX-double-) | يضبط قيمة عائمة تشير إلى زاوية الانحراف للإحداثي x عند تحويل نظام الإحداثيات. |
| [setSkewAngleY](#setSkewAngleY-double-) | يضبط قيمة عائمة تشير إلى زاوية الانحراف للإحداثي y عند تحويل نظام الإحداثيات. |

### GraphInfo {#GraphInfo--}
```
public GraphInfo()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ معلومات الرسومات.

**Returns:**
الكائن المستنسخ

### getColor {#getColor--}
```
public Color getColor()
```

يحصل على كائن {@code Color} الذي يشير إلى لون الرسم البياني.

**Returns:**
كائن يشير إلى اللون

### getDashArray {#getDashArray--}
```
public int[] getDashArray()
```

يحصل على مصفوفة الشرط.

**Returns:**
مصفوفة الفواصل

### getDashPhase {#getDashPhase--}
```
public int getDashPhase()
```

يحصل على مرحلة الشرط.

**Returns:**
مرحلة الفواصل.

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

يحصل على كائن {@code Color} الذي يشير إلى لون التعبئة للرسم البياني.

**Returns:**
كائن يشير إلى لون التعبئة

### getLineWidth {#getLineWidth--}
```
public float getLineWidth()
```

يحصل على قيمة عائمة تشير إلى عرض الخط للرسم البياني.

**Returns:**
قيمة تشير إلى عرض الخط.

### getRotationAngle {#getRotationAngle--}
```
public double getRotationAngle()
```

يحصل على قيمة عائمة تشير إلى زاوية الدوران لنظام الإحداثيات عند تحويل نظام الإحداثيات.

**Returns:**
قيمة double

### getScalingRateX {#getScalingRateX--}
```
public double getScalingRateX()
```

يحصل على قيمة عائمة تشير إلى معدل التحجيم للإحداثي x عند تحويل نظام الإحداثيات.

**Returns:**
قيمة double

### getScalingRateY {#getScalingRateY--}
```
public double getScalingRateY()
```

يحصل على قيمة عائمة تشير إلى معدل التحجيم للإحداثي y عند تحويل نظام الإحداثيات.

**Returns:**
قيمة double

### getSkewAngleX {#getSkewAngleX--}
```
public double getSkewAngleX()
```

يحصل على قيمة عائمة تشير إلى زاوية الانحراف للإحداثي x عند تحويل نظام الإحداثيات.

**Returns:**
قيمة double

### getSkewAngleY {#getSkewAngleY--}
```
public double getSkewAngleY()
```

يحصل على قيمة عائمة تشير إلى زاوية الانحراف للإحداثي y عند تحويل نظام الإحداثيات.

**Returns:**
قيمة double

### getX {#getX--}
```
public final double getX()
```

استرجع إحداثي X للحد العمودي عند استخدام TableAbsorber، وأرجع "-1" للحد الأفقي.

**Returns:**
قيمة double

### getY {#getY--}
```
public final double getY()
```

استرجع إحداثي Y للحد الأفقي عند استخدام TableAbsorber، وأرجع "-1" للحد العمودي.

**Returns:**
قيمة double

### isDoubled {#isDoubled--}
```
public boolean isDoubled()
```

يحصل على ما إذا كان الحد مزدوجًا.

**Returns:**
قيمة منطقية

### setColor {#setColor-com.aspose.pdf.Color-}
يضبط كائن {@code Color} الذي يشير إلى لون الرسم البياني.

### setDashArray {#setDashArray-int:A-}
```
public void setDashArray(int[] value)
```

يضبط مصفوفة الفواصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة الفواصل |

### setDashPhase {#setDashPhase-int-}
```
public void setDashPhase(int value)
```

يضبط مرحلة الفواصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مرحلة الفواصل. |

### setDoubled {#setDoubled-boolean-}
```
public void setDoubled(boolean value)
```

يضبط ما إذا كان الحد مزدوجًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
يضبط كائن {@code Color} الذي يشير إلى لون التعبئة للرسم البياني.

### setLineWidth {#setLineWidth-float-}
```
public void setLineWidth(float value)
```

يضبط قيمة عائمة تشير إلى عرض الخط للرسم البياني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة تشير إلى عرض الخط. |

### setRotationAngle {#setRotationAngle-double-}
```
public void setRotationAngle(double value)
```

يضبط قيمة عائمة تشير إلى زاوية دوران نظام الإحداثيات عند تحويل نظام الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setScalingRateX {#setScalingRateX-double-}
```
public void setScalingRateX(double value)
```

يضبط قيمة عائمة تشير إلى معدل التحجيم للإحداثي x عند تحويل نظام الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setScalingRateY {#setScalingRateY-double-}
```
public void setScalingRateY(double value)
```

يضبط قيمة عائمة تشير إلى معدل التحجيم للإحداثي y عند تحويل نظام الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setSkewAngleX {#setSkewAngleX-double-}
```
public void setSkewAngleX(double value)
```

يضبط قيمة عائمة تشير إلى زاوية الانحراف للإحداثي x عند تحويل نظام الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setSkewAngleY {#setSkewAngleY-double-}
```
public void setSkewAngleY(double value)
```

يضبط قيمة عائمة تشير إلى زاوية الانحراف للإحداثي y عند تحويل نظام الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
