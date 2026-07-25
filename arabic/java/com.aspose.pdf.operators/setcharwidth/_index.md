---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل d0 (تعيين عرض الحرف)."
type: docs
weight: 510
url: /ar/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

فئة تمثّل عامل d0 (تعيين عرض الحرف).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | منشئ. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getWx](#getWx--) | الإزاحة الأفقية لإحداثيات الحرف. |
| [getWy](#getWy--) | الإزاحة العمودية لإحداثيات الحرف. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

منشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| wx |  | الإزاحة الأفقية للرمز. |
| wy |  | الإزاحة العمودية للرمز. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getWx {#getWx--}
```
public double getWx()
```

الإزاحة الأفقية لإحداثيات الحرف.

**Returns:**
قيمة double

### getWy {#getWy--}
```
public double getWy()
```

الإزاحة العمودية لإحداثيات الحرف.

**Returns:**
قيمة double

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
تمثيل نصي للتمثيل
