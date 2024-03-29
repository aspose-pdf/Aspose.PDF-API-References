---
title: ImportDataTable
second_title: Aspose.PDF لمرجع .NET API
description: يستورد البيانات من System.Data.DataTable إلى Aspose.Pdf.Table
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

| معامل | يكتب | وصف |
| --- | --- | --- |
| importedDataTable | DataTable | مثيل المصدر System.Data.DataTable |
| isColumnNamesImported | Boolean | يحدد ما إذا كان سيتم استيراد أسماء الأعمدة كصف أول |
| firstFilledRow | Int32 | يحدد رقم الصف الأول على أساس الصفر في الجدول الهدف الذي سيبدأ منه الاستيراد ، إذا كان الصف الذي يحتوي على هذا الرقم (وبعض الصفوف السابقة) غائبًا في الجدول الهدف ، فسيتم إنشاؤه أولاً |
| firstFilledColumn | Int32 | يحدد عدد العمود الهدف الأول في الجدول الهدف ، يجب أن يكون العمود موجودًا في الجدول الهدف قبل بدء الاستيراد |

### أنظر أيضا

* class [Table](../../table)
* مساحة الاسم [Aspose.Pdf](../../table)
* المجسم [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

الواردات أDataTable كائن في الجدول .

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| importedDataTable | DataTable | الDataTable كائن سيتم استيراده. |
| isColumnNamesShown | Boolean | يحدد ما إذا كانت أسماء أعمدة جدول البيانات المصدر سيتم استيرادها كصف أول. |
| firstFilledRow | Int32 | يحدد رقم الصف الأول على أساس الصفر في الجدول الهدف الذي سيبدأ منه الاستيراد ، إذا كان الصف الذي يحتوي على هذا الرقم (وبعض الصفوف السابقة) غائبًا في الجدول الهدف ، فسيتم إنشاؤه أولاً |
| firstFilledColumn | Byte | يحدد عدد العمود الهدف الأول في الجدول الهدف ، يجب أن يكون العمود موجودًا في الجدول الهدف قبل بدء الاستيراد |
| maxRows | Int32 | الحد الأقصى لعدد الصفوف المراد استيرادها من الجدول المصدر. |
| maxColumns | Int32 | الحد الأقصى لعدد الأعمدة المراد استيرادها من الجدول المصدر. |
| isHtmlSupported | Boolean | يحدد ما إذا كان النص عبارة عن سلسلة html. |

### أنظر أيضا

* class [Table](../../table)
* مساحة الاسم [Aspose.Pdf](../../table)
* المجسم [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

الواردات أDataTable الكائن ، ولكن ليس ككيان كامل. يتم استيراد الصفوف والأعمدة المحددة فقط.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| importedDataTable | DataTable | الDataTable كائن سيتم استيراده. |
| sourceRowList | Int32[] | مصفوفة أعداد الصفوف في المصدرDataTableالكائن الذي يجب استيراده. يجب ألا تكون القائمة خالية ويجب أن تحتوي فقط على عدد من الصفوف الموجودة ، وإلا فسيتم طرح استثناء. |
| sourceColumnList | Int32[] | مصفوفة أعداد الأعمدة في المصدرDataTable الكائن الذي يجب استيراده. يجب ألا تكون القائمة خالية ويجب أن تحتوي فقط على عدد من الأعمدة الموجودة ، وإلا فسيتم طرح استثناء. |
| firstFilledRow | Int32 | رقم الصف الصفري للخلية الأولى في جدول targer الذي سيبدأ منه الاستيراد. إذا كان الجدول الهدف لا يحتوي على هذا الصف ، فسيتم إنشاؤه (وكل ما سبق إذا لزم الأمر) |
| firstFilledColumn | Int32 | رقم العمود الصفري للخلية الأولى في جدول targer الذي سيبدأ الاستيراد منه. يجب أن يحتوي الجدول الهدف على هذا العمود قبل بدء الاستيراد ، وإلا فسيتم طرح استثناء. |
| showColumnNamesAsFirstRow | Boolean | يحدد ما إذا كان سيتم استيراد أسماء أعمدة جدول بيانات المصدر كصف أول. |
| isHtmlSupported | Boolean | يحدد ما إذا كان النص عبارة عن سلسلة html. |

### أنظر أيضا

* class [Table](../../table)
* مساحة الاسم [Aspose.Pdf](../../table)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
