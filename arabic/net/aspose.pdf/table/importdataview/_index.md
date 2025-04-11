---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: طريقة الجدول. تستورد بيانات كائن DataView إلى الجدول
type: docs
weight: 270
url: /ar/net/aspose.pdf/table/importdataview/
---
## طريقة Table.ImportDataView

تستورد بيانات كائن DataView إلى الجدول.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceDataView | DataView | كائن DataView الذي سيتم استيراده. |
| isColumnNamesImported | Boolean | يشير إلى ما إذا كانت أسماء الأعمدة ستستورد كأول صف. |
| firstFilledRow | Int32 | رقم الصف المعتمد على الصفر للخلية الأولى في الجدول المستهدف الذي سيبدأ منه الاستيراد. إذا لم يحتوي الجدول المستهدف على ذلك الصف، فسيتم إنشاؤه (وكل الصفوف السابقة إذا لزم الأمر) |
| firstFilledColumn | Int32 | رقم العمود المعتمد على الصفر للخلية الأولى في الجدول المستهدف الذي سيبدأ منه الاستيراد. يجب أن يحتوي الجدول المستهدف على ذلك العمود قبل بدء الاستيراد، وإلا سيتم طرح استثناء. |
| maxRows | Int32 | الحد الأقصى لعدد الصفوف التي سيتم استيرادها من DataView المصدر. |
| maxColumns | Int32 | الحد الأقصى للأعمدة التي سيتم استيرادها من DataView المصدر. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)