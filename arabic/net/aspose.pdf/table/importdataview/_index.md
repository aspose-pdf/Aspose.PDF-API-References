---
title: "Table.ImportDataView"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Table. تستورد بيانات كائن DataView إلى الجدول"
type: docs
weight: 270
url: /ar/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

يستورد بيانات كائن DataView إلى الجدول.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sourceDataView | DataView | كائن DataView المراد استيراده. |
| isColumnNamesImported | Boolean | يشير إلى ما إذا كانت أسماء الأعمدة ستُستورد كصف أول. |
| firstFilledRow | Int32 | رقم الصف المستند إلى الصفر للخلية الأولى في الجدول targer الذي سيبدأ منه الاستيراد. إذا لم يحتوي الجدول الهدف على ذلك الصف، فسيتم إنشاؤه (مع جميع الصفوف السابقة إذا لزم الأمر). |
| firstFilledColumn | Int32 | رقم العمود الصفري للخلية الأولى في الجدول الهدف الذي سيبدأ منه الاستيراد. يجب أن يحتوي الجدول الهدف على ذلك العمود قبل بدء الاستيراد، وإلا سيتم رمي استثناء. |
| maxRows | Int32 | الحد الأقصى لعدد الصفوف التي سيتم استيرادها من DataView المصدر. |
| maxColumns | Int32 | الحد الأقصى لعدد الأعمدة التي سيتم استيرادها من DataView المصدر. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


