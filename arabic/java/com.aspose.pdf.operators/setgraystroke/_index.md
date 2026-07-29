---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل مستوى الرمادي للعمليات المتسلسلة."
type: docs
weight: 650
url: /ar/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

فئة تمثل مستوى الرمادي للعمليات المتسلسلة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | يقوم بتهيئة المشغل باللون المحدد. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getColor](#getColor--) | يعيد اللون المحدد بواسطة المشغل. |
| [getGray](#getGray--) | يحصل أو يضبط مستوى قيمة الرمادي. |
| [setGray](#setGray-double-) | يحصل أو يضبط مستوى قيمة الرمادي. |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

يقوم بتهيئة المشغل باللون المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رمادي |  | مستوى قيمة الرمادي. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getColor {#getColor--}
```
public Color getColor()
```

يعيد اللون المحدد بواسطة المشغل.

**Returns:**
اللون المحدد بواسطة المشغل.

### getGray {#getGray--}
```
public final double getGray()
```

يحصل أو يضبط مستوى قيمة الرمادي.

**Returns:**
قيمة double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

يحصل أو يضبط مستوى قيمة الرمادي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toString {#toString--}
```
public String toString()
```

يرجع تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
