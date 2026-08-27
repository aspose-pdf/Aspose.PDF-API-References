---
title: "SetRGBColor"
linktitle: "SetRGBColor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معامل rg (تعيين لون RGB للمعاملات غير المتسلسلة)."
type: docs
weight: 710
url: /ar/java/com.aspose.pdf.operators/setrgbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColor

```
public class SetRGBColor extends SetColorOperator
```

فئة تمثل معامل rg (تعيين لون RGB للمعاملات غير المتسلسلة).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetRGBColor](#SetRGBColor-java.awt.Color-) | يُهيئ العامل باللون. |
| [SetRGBColor](#SetRGBColor-double-double-double-) | منشئ لكتابة البرنامج. |
| [SetRGBColor](#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getB](#getB--) | يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | يعيد اللون المحدد بواسطة المشغل. |
| [getG](#getG--) | يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0 |
| [getR](#getR--) | يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0 |
| [setB](#setB-double-) | يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0 |
| [setG](#setG-double-) | يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0 |
| [setR](#setR-double-) | يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0 |
| [toString](#toString--) | يعيد تمثيل النص للمشغل. |

### SetRGBColor {#SetRGBColor-java.awt.Color-}
يُهيئ العامل باللون.

### SetRGBColor {#SetRGBColor-double-double-double-}
```
public SetRGBColor(double r, double g, double b)
```

منشئ لكتابة البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r |  | مستوى الأحمر من 0.0 إلى 1.0 |
| g |  | مستوى الأخضر من 0.0 إلى 1.0 |
| b |  | مستوى الأزرق من 0.0 إلى 1.0 |

### SetRGBColor {#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getB {#getB--}
```
public final double getB()
```

يحصل أو يضبط المكوّن الأزرق. القيمة: مستوى الأزرق من 0.0 إلى 1.0

**Returns:**
قيمة قابلة للتنفيذ

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

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

### getR {#getR--}
```
public final double getR()
```

يحصل أو يضبط المكوّن الأحمر. القيمة: مستوى الأحمر من 0.0 إلى 1.0

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

### setG {#setG-double-}
```
public final void setG(double value)
```

يحصل أو يضبط المكوّن الأخضر. القيمة: مستوى الأخضر من 0.0 إلى 1.0

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

### toString {#toString--}
```
public String toString()
```

يعيد تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
