---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل K (تعيين لون CMYK للعمليات المتسلسلة)."
type: docs
weight: 540
url: /ar/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

فئة تمثّل عامل K (تعيين لون CMYK للعمليات المتسلسلة).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | يقوم بتهيئة المشغل. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getC](#getC--) | يحصل أو يضبط المكوّن السماوي. |
| [getColor](#getColor--) | يرجع لون RGB |
| [getK](#getK--) | يحصل أو يضبط المكوّن الأسود. |
| [getM](#getM--) | يحصل أو يضبط المكوّن الأرجواني. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | يحصل أو يضبط المكوّن الأصفر. |
| [setC](#setC-double-) | يحصل أو يضبط المكوّن السماوي. |
| [setK](#setK-double-) | يحصل أو يضبط المكوّن الأسود. |
| [setM](#setM-double-) | يحصل أو يضبط المكوّن الأرجواني. |
| [setY](#setY-double-) | يحصل أو يضبط المكوّن الأصفر. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

يقوم بتهيئة المشغل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c |  | مستوى السماوي من 0.0 إلى 1.0 |
| m |  | مستوى الأرجواني من 0.0 إلى 1.0 |
| y |  | مستوى الأصفر من 0.0 إلى 1.0 |
| k |  | مستوى الأسود من 0.0 إلى 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

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

يرجع لون RGB

**Returns:**
اللون المحدد بواسطة المشغل.

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

يحصل أو يضبط المكوّن الأصفر.

**Returns:**
قيمة قابلة للتنفيذ

### setC {#setC-double-}
```
public final void setC(double value)
```

يحصل أو يضبط المكوّن السماوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |

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

### setY {#setY-double-}
```
public final void setY(double value)
```

يحصل أو يضبط المكوّن الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة قابلة للتنفيذ |
