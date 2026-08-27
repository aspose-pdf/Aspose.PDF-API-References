---
title: "Do"
linktitle: "Do"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل عامل Do (استدعاء XObject)."
type: docs
weight: 180
url: /ar/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

فئة تمثّل عامل Do (استدعاء XObject).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Do](#Do--) | ينشئ معامل Do جديد. يُستخدم لاسترجاع جميع معاملات Do، أي دون فحص أسماء معطياتها. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | ينشئ معامل Do جديد. يُستخدم لاسترجاع جميع معاملات Do، أي دون فحص أسماء معطياتها. |
| [Do](#Do-java.lang.String-) | ينشئ معامل Do جديد. يُستخدم لاسترجاع جميع معاملات Do، أي دون فحص أسماء معطياتها. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل كائن الزائر لمعالجة المشغل. |
| [getCommandName](#getCommandName--) | يحصل على اسم الأمر |
| [getName](#getName--) | احصل على اسم معامل XObject للمعامل. |
| [setName](#setName-java.lang.String-) | عيّن اسم معامل XObject للمعامل. |
| [toCommand](#toCommand--) | للاستخدام الداخلي فقط! |
| [toString](#toString--) | يرجع تمثيل النص للمشغل. |

### Do {#Do--}
```
public Do()
```

ينشئ معامل Do جديد. يُستخدم لاسترجاع جميع معاملات Do، أي دون فحص أسماء معطياتها.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
ينشئ معامل Do جديد. يُستخدم لاسترجاع جميع معاملات Do، أي دون فحص أسماء معطياتها.

### Do {#Do-java.lang.String-}
ينشئ معامل Do جديد. يُستخدم لاسترجاع جميع معاملات Do، أي دون فحص أسماء معطياتها.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل كائن الزائر لمعالجة المشغل.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

يحصل على اسم الأمر

**Returns:**
قيمة سلسلة

### getName {#getName--}
```
public String getName()
```

احصل على اسم معامل XObject للمعامل.

**Returns:**
قيمة سلسلة

### setName {#setName-java.lang.String-}
عيّن اسم معامل XObject للمعامل.

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
