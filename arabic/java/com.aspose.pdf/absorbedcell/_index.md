---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خلية جدول موجودة في الصفحة"
type: docs
weight: 10
url: /ar/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

يمثل خلية جدول موجودة في الصفحة

## الطرق

| طريقة | الوصف |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | يقارن كائن AbsorbedCell الحالي بكائن AbsorbedCell آخر ويعيد عددًا صحيحًا يشير إلى ما إذا كان الكائن الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| [getBorderInfo](#getBorderInfo--) | إرجاع معلومات الحدود للخلية عندما تكون الخاصية FlowEngine.TableAbsorber.UseFlowEngine مضبوطة على true. |
| [getColSpan](#getColSpan--) | أرجع عدد الأعمدة التي يجب أن يمتدها الخلية عندما يتم تعيين خاصية TableAbsorber.UseFlowEngine إلى true. |
| [getRectangle](#getRectangle--) | يحصل على المستطيل الذي يصف موضع الخلية على الصفحة |
| [getTextFragments](#getTextFragments--) | يحصل على مجموعة من كائنات {@code TextFragment} التي تصف النص الموجود في الخلية |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
يقارن كائن AbsorbedCell الحالي بكائن AbsorbedCell آخر ويعيد عددًا صحيحًا يشير إلى ما إذا كان الكائن الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

إرجاع معلومات الحدود للخلية عندما تكون الخاصية FlowEngine.TableAbsorber.UseFlowEngine مضبوطة على true.

**Returns:**
مثيل BorderInfo

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

أرجع عدد الأعمدة التي يجب أن يمتدها الخلية عندما يتم تعيين خاصية TableAbsorber.UseFlowEngine إلى true.

**Returns:**
قيمة int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على المستطيل الذي يصف موضع الخلية على الصفحة

**Returns:**
كائن Rectangle

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

يحصل على مجموعة من كائنات {@code TextFragment} التي تصف النص الموجود في الخلية

**Returns:**
كائن TextFragmentCollection
