---
title: "DP"
linktitle: "DP"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل DP (تعيين نقطة المحتوى المعلَّم)."
type: docs
weight: 190
url: /ar/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

فئة تمثّل عامل DP (تعيين نقطة المحتوى المعلَّم).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | منشئ لفئة operator. |
| [DP](#DP-java.lang.String-) | يقوم بتهيئة المشغل. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | يحصل على قاموس الخصائص |
| [getTag](#getTag--) | يحصل على علامة المحتوى المميز |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | يضبط قاموس الخصائص |
| [setTag](#setTag-java.lang.String-) | يضبط علامة المحتوى المميز |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
منشئ لفئة operator.

### DP {#DP-java.lang.String-}
يقوم بتهيئة المشغل.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

يحصل على قاموس الخصائص

**Returns:**
قيمة IPdfDictionary

### getTag {#getTag--}
```
public String getTag()
```

يحصل على علامة المحتوى المميز

**Returns:**
قيمة سلسلة

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
يضبط قاموس الخصائص

### setTag {#setTag-java.lang.String-}
يضبط علامة المحتوى المميز

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

يرجع تمثيل النص للمشغل.

**Returns:**
تمثيل النص للمشغل.
