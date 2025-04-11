---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: 表方法。将数据从 System.Data.DataTable 导入到 Aspose.Pdf.Table
type: docs
weight: 260
url: /zh/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

将数据从 System.Data.DataTable 导入到 Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| importedDataTable | DataTable | System.Data.DataTable 的源实例 |
| isColumnNamesImported | Boolean | 指定列名是否将作为第一行导入 |
| firstFilledRow | Int32 | 指定目标表中导入开始的第一行的零基数编号，如果目标表中不存在该行（及一些之前的行），则会首先创建它们 |
| firstFilledColumn | Int32 | 指定目标表中第一列的编号，导入开始前该列必须存在于目标表中 |

### 另请参见

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

将 DataTable 对象导入到表中。

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| importedDataTable | DataTable | 要导入的 DataTable 对象。 |
| isColumnNamesShown | Boolean | 指定源数据表的列名是否将作为第一行导入。 |
| firstFilledRow | Int32 | 指定目标表中导入开始的第一行的零基数编号，如果目标表中不存在该行（及一些之前的行），则会首先创建它们 |
| firstFilledColumn | Byte | 指定目标表中第一列的编号，导入开始前该列必须存在于目标表中 |
| maxRows | Int32 | 从源表中导入的最大行数。 |
| maxColumns | Int32 | 从源表中导入的最大列数。 |
| isHtmlSupported | Boolean | 指定文本是否为 HTML 字符串。 |

### 另请参见

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

导入 DataTable 对象，但不是作为整体实体。仅导入指定的行和列。

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| importedDataTable | DataTable | 要导入的 DataTable 对象。 |
| sourceRowList | Int32[] | 必须导入的源 DataTable 对象中行的编号数组。列表不能为空，且必须仅包含现有行的编号，否则将抛出异常。 |
| sourceColumnList | Int32[] | 必须导入的源 DataTable 对象中列的编号数组。列表不能为空，且必须仅包含现有列的编号，否则将抛出异常。 |
| firstFilledRow | Int32 | 目标表中导入开始的第一个单元格的零基数行编号。如果目标表中不包含该行，则会创建该行（如有必要，还会创建所有之前的行） |
| firstFilledColumn | Int32 | 目标表中导入开始的第一个单元格的零基数列编号。目标表必须在导入开始前包含该列，否则将抛出异常。 |
| showColumnNamesAsFirstRow | Boolean | 指定源数据表的列名是否将作为第一行导入。 |
| isHtmlSupported | Boolean | 指定文本是否为 HTML 字符串。 |

### 另请参见

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)