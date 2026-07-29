---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معامل i (تعيين تسامح الانبساط)."
type: docs
weight: 620
url: /ar/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

فئة تمثل معامل i (تعيين تسامح الانبساط).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetFlat](#SetFlat-double-) | يقوم بتهيئة المشغل. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن زائر لمعالجة المشغل. |
| [getFlatness](#getFlatness--) | يحصل على السطحية. |
| [setFlatness](#setFlatness-double-) | يضبط السطحية. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

يقوم بتهيئة المشغل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السطحية |  | قيمة السطحية. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن زائر لمعالجة المشغل.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

يحصل على السطحية.

**Returns:**
قيمة double

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

يضبط السطحية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

للاستخدام الداخلي فقط!

**Returns:**
قيمة ICommand كائن ICommand
