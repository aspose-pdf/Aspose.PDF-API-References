---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جدول موجود في الصفحة"
type: docs
weight: 30
url: /ar/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

يمثل جدول موجود في الصفحة

## الطرق

| طريقة | الوصف |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | يقارن كائن AbsorbedTable الحالي بكائن AbsorbedTable آخر ويعيد عددًا صحيحًا يشير إلى ما إذا كان الكائن الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| [getPageNum](#getPageNum--) | يحصل على رقم الصفحة التي تحتوي على هذا الجدول |
| [getRectangle](#getRectangle--) | يحصل على المستطيل الذي يصف موضع الجدول على الصفحة |
| [getRowList](#getRowList--) | <p> يحصل على IList للقراءة فقط يحتوي على صفوف الجدول </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
يقارن كائن AbsorbedTable الحالي بكائن AbsorbedTable آخر ويعيد عددًا صحيحًا يشير إلى ما إذا كان الكائن الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

يحصل على رقم الصفحة التي تحتوي على هذا الجدول

**Returns:**
قيمة int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على المستطيل الذي يصف موضع الجدول على الصفحة

**Returns:**
كائن Rectangle

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> يحصل على IList للقراءة فقط يحتوي على صفوف الجدول </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} كائن
