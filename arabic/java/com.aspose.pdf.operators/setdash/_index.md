---
title: "SetDash"
linktitle: "SetDash"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معامل d (تعيين نمط الشرط للخط)."
type: docs
weight: 610
url: /ar/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

فئة تمثل معامل d (تعيين نمط الشرط للخط).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | ينشئ مشغل تعيين نمط الشرط. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getPattern](#getPattern--) | نمط الشرط. يجب أن تكون عناصر المصفوفة أرقامًا تحدد أطوال الشرط والفواصل المتناوبة. في حالة مصفوفة ذات عنصر واحد تكون أطوال الشرط والفاصل متساوية. |
| [getPhase](#getPhase--) | مرحلة الشرط. قبل بدء رسم مسار، يجب تدوير مصفوفة الشرط، مع جمع أطوال الشرط والفواصل. عندما يساوي الطول المتراكم القيمة المحددة بواسطة مرحلة الشرط، يبدأ رسم المسار، وتُستخدم مصفوفة الشرط بشكل دوري من تلك النقطة فصاعدًا. |
| [setPattern](#setPattern-int:A-) | نمط الشرط. يجب أن تكون عناصر المصفوفة أرقامًا تحدد أطوال الشرط والفواصل المتناوبة. في حالة مصفوفة ذات عنصر واحد تكون أطوال الشرط والفاصل متساوية. |
| [setPhase](#setPhase-int-) | مرحلة الشرط. قبل بدء رسم مسار، يجب تدوير مصفوفة الشرط، مع جمع أطوال الشرط والفواصل. عندما يساوي الطول المتراكم القيمة المحددة بواسطة مرحلة الشرط، يبدأ رسم المسار، وتُستخدم مصفوفة الشرط بشكل دوري من تلك النقطة فصاعدًا. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يحصل على تمثيل النص للمعامل. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

ينشئ مشغل تعيين نمط الشرط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نمط |  | مصفوفة تُحدد نمط الشرط. |
| المرحلة |  | مرحلة الشرط. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

نمط الشرط. يجب أن تكون عناصر المصفوفة أرقامًا تحدد أطوال الشرط والفواصل المتناوبة. في حالة مصفوفة ذات عنصر واحد تكون أطوال الشرط والفاصل متساوية.

**Returns:**
مصفوفة int

### getPhase {#getPhase--}
```
public int getPhase()
```

مرحلة الشرط. قبل بدء رسم مسار، يجب تدوير مصفوفة الشرط، مع جمع أطوال الشرط والفواصل. عندما يساوي الطول المتراكم القيمة المحددة بواسطة مرحلة الشرط، يبدأ رسم المسار، وتُستخدم مصفوفة الشرط بشكل دوري من تلك النقطة فصاعدًا.

**Returns:**
قيمة int

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

نمط الشرط. يجب أن تكون عناصر المصفوفة أرقامًا تحدد أطوال الشرط والفواصل المتناوبة. في حالة مصفوفة ذات عنصر واحد تكون أطوال الشرط والفاصل متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة int |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

مرحلة الشرط. قبل بدء رسم مسار، يجب تدوير مصفوفة الشرط، مع جمع أطوال الشرط والفواصل. عندما يساوي الطول المتراكم القيمة المحددة بواسطة مرحلة الشرط، يبدأ رسم المسار، وتُستخدم مصفوفة الشرط بشكل دوري من تلك النقطة فصاعدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

للاستخدام الداخلي فقط!

**Returns:**
قيمة ICommand كائن ICommand

### toString {#toString--}
```
public String toString()
```

يحصل على تمثيل النص للمعامل.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
