---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معامل TL (تعيين ارتفاع السطر للنص)."
type: docs
weight: 740
url: /ar/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

فئة تمثل معامل TL (تعيين ارتفاع السطر للنص).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | منشئ لمعامل النص المتقدم. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getLeading](#getLeading--) | يحصل على تقدم النص. |
| [setLeading](#setLeading-double-) | يضبط تقدم النص. |
| [toString](#toString--) | ينتج رمز النص للمشغل. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

منشئ لمعامل النص المتقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leading |  | تقدم النص. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getLeading {#getLeading--}
```
public double getLeading()
```

يحصل على تقدم النص.

**Returns:**
قيمة double

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

يضبط تقدم النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toString {#toString--}
```
public String toString()
```

ينتج رمز النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
