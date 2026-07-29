---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معامل SC لتعيين اللون لمعاملات اللون المتسلسلة."
type: docs
weight: 600
url: /ar/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

فئة تمثل معامل SC لتعيين اللون لمعاملات اللون المتسلسلة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | يقوم بتهيئة المشغل. |
| [SetColorStroke](#SetColorStroke-double-) | تعيين اللون لمشغلات التحديد لأماكن اللون DeviceGray و CalGray و Indexed. |
| [SetColorStroke](#SetColorStroke-double:A-) | منشئ يسمح بتعيين مكونات اللون. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | تعيين اللون لمشغل التحديد لأماكن اللون DeviceRGB و CalRGB و Lab. |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | تعيين اللون لمشغل التحديد لمكان اللون CMYK. |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | يقوم بتهيئة المشغل. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getB](#getB--) | يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0 |
| [getC](#getC--) | يحصل أو يضبط المكوّن السماوي. |
| [getColor](#getColor--) | يعيد اللون المحدد بواسطة المشغل. |
| [getG](#getG--) | يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0 |
| [getK](#getK--) | يحصل أو يضبط المكوّن الأسود. |
| [getM](#getM--) | يحصل أو يضبط المكوّن الأرجواني. |
| [getR](#getR--) | يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0 |
| [getY](#getY--) | يحصل أو يضبط المكوّن الأصفر. |
| [setB](#setB-double-) | يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0 |
| [setC](#setC-double-) | يحصل أو يضبط المكوّن السماوي. |
| [setG](#setG-double-) | يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0 |
| [setK](#setK-double-) | يحصل أو يضبط المكوّن الأسود. |
| [setM](#setM-double-) | يحصل أو يضبط المكوّن الأرجواني. |
| [setR](#setR-double-) | يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0 |
| [setY](#setY-double-) | يحصل أو يضبط المكوّن الأصفر. |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

يقوم بتهيئة المشغل.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

تعيين اللون لمشغلات التحديد لأماكن اللون DeviceGray و CalGray و Indexed.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g |  | قيمة اللون. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

منشئ يسمح بتعيين مكونات اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| لون |  | مصفوفة من مكونات اللون. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

تعيين اللون لمشغل التحديد لأماكن اللون DeviceRGB و CalRGB و Lab.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r |  | المكوّن الأحمر. |
| g |  | المكوّن الأخضر. |
| b |  | المكوّن الأزرق. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

تعيين اللون لمشغل التحديد لمكان اللون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c |  | المكوّن السماوي. |
| m |  | المكوّن الأرجواني. |
| y |  | المكوّن الأصفر. |
| k |  | المكوّن الأسود. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
يقوم بتهيئة المشغل.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getB {#getB--}
```
public final double getB()
```

يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0

**Returns:**
قيمة قابلة للتنفيذ

### getC {#getC--}
```
public final double getC()
```

يحصل أو يضبط المكوّن السماوي.

**Returns:**
قيمة قابلة للتنفيذ

### getColor {#getColor--}
```
public Color getColor()
```

يعيد اللون المحدد بواسطة المشغل.

**Returns:**
اللون المحدد بواسطة المشغل.

### getG {#getG--}
```
public final double getG()
```

يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0

**Returns:**
قيمة قابلة للتنفيذ

### getK {#getK--}
```
public final double getK()
```

يحصل أو يضبط المكوّن الأسود.

**Returns:**
قيمة قابلة للتنفيذ

### getM {#getM--}
```
public final double getM()
```

يحصل أو يضبط المكوّن الأرجواني.

**Returns:**
قيمة قابلة للتنفيذ

### getR {#getR--}
```
public final double getR()
```

يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0

**Returns:**
قيمة قابلة للتنفيذ

### getY {#getY--}
```
public final double getY()
```

يحصل أو يضبط المكوّن الأصفر.

**Returns:**
قيمة قابلة للتنفيذ

### setB {#setB-double-}
```
public final void setB(double value)
```

يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |

### setC {#setC-double-}
```
public final void setC(double value)
```

يحصل أو يضبط المكوّن السماوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |

### setG {#setG-double-}
```
public final void setG(double value)
```

يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setK {#setK-double-}
```
public final void setK(double value)
```

يحصل أو يضبط المكوّن الأسود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |

### setM {#setM-double-}
```
public final void setM(double value)
```

يحصل أو يضبط المكوّن الأرجواني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |

### setR {#setR-double-}
```
public final void setR(double value)
```

يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |

### setY {#setY-double-}
```
public final void setY(double value)
```

يحصل أو يضبط المكوّن الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |
