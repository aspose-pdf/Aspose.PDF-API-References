---
title: "Table.ImportDataTable"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Table. تستورد البيانات من System.Data.DataTable إلى Aspose.Pdf.Table."
type: docs
weight: 260
url: /ar/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

يستورد البيانات من System.Data.DataTable إلى Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| importedDataTable | DataTable | مثيل المصدر من System.Data.DataTable |
| isColumnNamesImported | Boolean | يحدد ما إذا كان سيتم استيراد أسماء الأعمدة كصف أول. |
| firstFilledRow | Int32 | يحدد رقم الصف الأول في الجدول الهدف بدءًا من الصفر الذي سيبدأ منه الاستيراد؛ إذا كان الصف بهذا الرقم (وبعض الصفوف السابقة) غير موجود في الجدول الهدف، فسيتم إنشاؤه أولاً. |
| firstFilledColumn | Int32 | يحدد رقم العمود الأول المستهدف في الجدول الهدف، يجب أن يكون العمود موجودًا في الجدول الهدف قبل بدء الاستيراد. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

يستورد كائن DataTable إلى الجدول.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| importedDataTable | DataTable | كائن DataTable المراد استيراده. |
| isColumnNamesShown | Boolean | يحدد ما إذا كانت أسماء الأعمدة في جدول البيانات المصدر سيتم استيرادها كصف أول. |
| firstFilledRow | Int32 | يحدد رقم الصف الأول في الجدول الهدف بدءًا من الصفر الذي سيبدأ منه الاستيراد؛ إذا كان الصف بهذا الرقم (وبعض الصفوف السابقة) غير موجود في الجدول الهدف، فسيتم إنشاؤه أولاً. |
| firstFilledColumn | Byte | يحدد رقم العمود الأول المستهدف في الجدول الهدف، يجب أن يكون العمود موجودًا في الجدول الهدف قبل بدء الاستيراد. |
| maxRows | Int32 | الحد الأقصى لعدد الصفوف التي سيتم استيرادها من الجدول المصدر. |
| maxColumns | Int32 | الحد الأقصى لعدد الأعمدة التي سيتم استيرادها من الجدول المصدر. |
| isHtmlSupported | Boolean | يحدد ما إذا كان النص عبارة عن سلسلة HTML. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

يستورد كائن DataTable، ولكن ليس ككيان كامل. يتم استيراد الصفوف والأعمدة المحددة فقط.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| importedDataTable | DataTable | كائن DataTable المراد استيراده. |
| sourceRowList | Int32[] | المصفوفة التي تحتوي على أرقام الصفوف في كائن DataTable المصدر التي يجب استيرادها. يجب ألا تكون القائمة فارغة ويجب أن تحتوي فقط على أرقام الصفوف الموجودة، وإلا سيتم رمي استثناء. |
| sourceColumnList | Int32[] | المصفوفة التي تحتوي على أرقام الأعمدة في كائن DataTable المصدر التي يجب استيرادها. يجب ألا تكون القائمة فارغة ويجب أن تحتوي فقط على أرقام الأعمدة الموجودة، وإلا سيتم رمي استثناء. |
| firstFilledRow | Int32 | رقم الصف المستند إلى الصفر للخلية الأولى في الجدول targer الذي سيبدأ منه الاستيراد. إذا لم يحتوي الجدول الهدف على ذلك الصف، فسيتم إنشاؤه (مع جميع الصفوف السابقة إذا لزم الأمر). |
| firstFilledColumn | Int32 | رقم العمود المستند إلى الصفر للخلية الأولى في الجدول targer الذي سيبدأ منه الاستيراد. يجب أن يحتوي الجدول الهدف على ذلك العمود قبل بدء الاستيراد، وإلا سيتم رمي استثناء. |
| showColumnNamesAsFirstRow | Boolean | يحدد ما إذا كانت أسماء الأعمدة في جدول البيانات المصدر سيتم استيرادها كصف أول. |
| isHtmlSupported | Boolean | يحدد ما إذا كان النص عبارة عن سلسلة HTML. |

### انظر أيضًا

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


