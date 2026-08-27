---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل d1 (تعيين الحرف ومربع الحد)."
type: docs
weight: 520
url: /ar/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

فئة تمثّل عامل d1 (تعيين الحرف ومربع الحد).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | يُهيئ عامل SetCharWidthBoundingBox. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | منشئ لفئة operator. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getLlx](#getLlx--) | الإحداثي الأفقي للزاوية السفلية اليسرى للمستطيل المحيط. |
| [getLly](#getLly--) | الإحداثي العمودي للزاوية السفلية اليسرى للمستطيل المحيط. |
| [getUrx](#getUrx--) | الإحداثي الأفقي للزاوية العليا اليمنى للمستطيل المحيط. |
| [getUry](#getUry--) | الإحداثي العمودي للزاوية العليا اليمنى للمستطيل المحيط. |
| [getWx](#getWx--) | الإزاحة الأفقية للرمز. |
| [getWy](#getWy--) | الإزاحة العمودية للرمز. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

يُهيئ عامل SetCharWidthBoundingBox.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| wx |  | يشير إلى الإزاحة الأفقية في إحداثيات الرمز. |
| wy |  | يشير إلى الإزاحة العمودية في إحداثيات الرمز. يجب أن تكون 0. |
| llx |  | يشير إلى إحداثي X للزاوية السفلية اليسرى. |
| lly |  | يشير إلى إحداثي Y للزاوية السفلية اليسرى. |
| urx |  | يشير إلى إحداثي X للزاوية العليا اليمنى. |
| ury |  | يشير إلى إحداثي Y للزاوية العليا اليمنى. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
منشئ لفئة operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getLlx {#getLlx--}
```
public double getLlx()
```

الإحداثي الأفقي للزاوية السفلية اليسرى للمستطيل المحيط.

**Returns:**
قيمة double

### getLly {#getLly--}
```
public double getLly()
```

الإحداثي العمودي للزاوية السفلية اليسرى للمستطيل المحيط.

**Returns:**
قيمة double

### getUrx {#getUrx--}
```
public double getUrx()
```

الإحداثي الأفقي للزاوية العليا اليمنى للمستطيل المحيط.

**Returns:**
قيمة double

### getUry {#getUry--}
```
public double getUry()
```

الإحداثي العمودي للزاوية العليا اليمنى للمستطيل المحيط.

**Returns:**
قيمة double

### getWx {#getWx--}
```
public double getWx()
```

الإزاحة الأفقية للرمز.

**Returns:**
قيمة double

### getWy {#getWy--}
```
public double getWy()
```

الإزاحة العمودية للرمز.

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
