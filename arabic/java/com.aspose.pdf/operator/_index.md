---
title: "Operator"
linktitle: "Operator"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة مجردة تمثل المشغل."
type: docs
weight: 3180
url: /ar/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

فئة مجردة تمثل المشغل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | للاستخدام الداخلي فقط! |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | يقبل الزائر IOperatorSelector الذي يوفر معالجة العوامل. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | ينشئ عاملًا باسم مثيل com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | يقارن هذا المثيل مع الكائن المعطى. |
| [getCommand](#getCommand--) | يحصل على الأمر |
| [getCommandName](#getCommandName--) | يحصل على اسم العامل. |
| [getIndex](#getIndex--) | احصل على فهرس العامل في قائمة عوامل الصفحة. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | يحدد ما إذا كان العامل هو العامل المسؤول عن إخراج النص (Tj، TJ، إلخ). |
| [setIndex](#setIndex-int-) | تعيين فهرس المشغل في قائمة مشغلي الصفحة. |
| [toString](#toString--) | يحوّل الأمر والمعلمات إلى تمثيل نصي. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | يقارن هذا المثيل مع الكائن المعطى. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
للاستخدام الداخلي فقط!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
يقبل الزائر IOperatorSelector الذي يوفر معالجة العوامل.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
ينشئ عاملًا باسم مثيل com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
يقارن هذا المثيل مع الكائن المعطى.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

يحصل على الأمر

**Returns:**
كائن ICommand

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

يحصل على اسم العامل.

**Returns:**
قيمة سلسلة

### getIndex {#getIndex--}
```
public int getIndex()
```

احصل على فهرس العامل في قائمة عوامل الصفحة.

**Returns:**
قيمة int

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
يحدد ما إذا كان العامل هو العامل المسؤول عن إخراج النص (Tj، TJ، إلخ).

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

تعيين فهرس المشغل في قائمة مشغلي الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### toString {#toString--}
```
public String toString()
```

يحوّل الأمر والمعلمات إلى تمثيل نصي.

**Returns:**
نص المشغل

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
يقارن هذا المثيل مع الكائن المعطى.
