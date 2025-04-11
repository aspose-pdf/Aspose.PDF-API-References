---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: طريقة الجدول. تستورد البيانات من System.Data.DataTable إلى Aspose.Pdf.Table
type: docs
weight: 260
url: /ar/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

تستورد البيانات من System.Data.DataTable إلى Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| importedDataTable | DataTable | مثيل المصدر من System.Data.DataTable |
| isColumnNamesImported | Boolean | يحدد ما إذا كانت أسماء الأعمدة ستستورد كأول صف |
| firstFilledRow | Int32 | يحدد الرقم الصف الأول في الجدول المستهدف الذي ستبدأ منه الاستيراد، إذا كان الصف بالرقم المذكور (وبعض الصفوف السابقة) غير موجود في الجدول المستهدف، سيتم إنشاؤها أولاً |
| firstFilledColumn | Int32 | يحدد رقم أول عمود مستهدف في الجدول المستهدف، يجب أن يكون العمود موجودًا في الجدول المستهدف قبل بدء الاستيراد |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

تستورد كائن DataTable إلى الجدول.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| importedDataTable | DataTable | كائن DataTable الذي سيتم استيراده. |
| isColumnNamesShown | Boolean | يحدد ما إذا كانت أسماء أعمدة جدول البيانات المصدر ستستورد كأول صف. |
| firstFilledRow | Int32 | يحدد الرقم الصف الأول في الجدول المستهدف الذي ستبدأ منه الاستيراد، إذا كان الصف بالرقم المذكور (وبعض الصفوف السابقة) غير موجود في الجدول المستهدف، سيتم إنشاؤها أولاً |
| firstFilledColumn | Byte | يحدد رقم أول عمود مستهدف في الجدول المستهدف، يجب أن يكون العمود موجودًا في الجدول المستهدف قبل بدء الاستيراد |
| maxRows | Int32 | الحد الأقصى لعدد الصفوف التي سيتم استيرادها من الجدول المصدر. |
| maxColumns | Int32 | الحد الأقصى لعدد الأعمدة التي سيتم استيرادها من الجدول المصدر. |
| isHtmlSupported | Boolean | يحدد ما إذا كان النص سلسلة HTML. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

تستورد كائن DataTable، ولكن ليس ككيان كامل. يتم استيراد الصفوف والأعمدة المحددة فقط.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| importedDataTable | DataTable | كائن DataTable الذي سيتم استيراده. |
| sourceRowList | Int32[] | مصفوفة من أرقام الصفوف في كائن DataTable المصدر التي يجب استيرادها. يجب أن تكون القائمة غير فارغة ويجب أن تحتوي فقط على أرقام الصفوف الموجودة، وإلا سيتم طرح استثناء. |
| sourceColumnList | Int32[] | مصفوفة من أرقام الأعمدة في كائن DataTable المصدر التي يجب استيرادها. يجب أن تكون القائمة غير فارغة ويجب أن تحتوي فقط على أرقام الأعمدة الموجودة، وإلا سيتم طرح استثناء. |
| firstFilledRow | Int32 | الرقم الصف الأول في الجدول المستهدف الذي ستبدأ منه الاستيراد. إذا كان الجدول المستهدف لا يحتوي على ذلك الصف، سيتم إنشاؤه (وكل الصفوف السابقة إذا لزم الأمر) |
| firstFilledColumn | Int32 | الرقم العمود الأول في الجدول المستهدف الذي ستبدأ منه الاستيراد. يجب أن يحتوي الجدول المستهدف على ذلك العمود قبل بدء الاستيراد، وإلا سيتم طرح استثناء. |
| showColumnNamesAsFirstRow | Boolean | يحدد ما إذا كانت أسماء أعمدة جدول البيانات المصدر ستستورد كأول صف. |
| isHtmlSupported | Boolean | يحدد ما إذا كان النص سلسلة HTML. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)