---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Table method. Imports data from System.Data.DataTable into Aspose.Pdf.Table
type: docs
weight: 260
url: /net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Imports data from System.Data.DataTable into Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parameter | Type | Description |
| --- | --- | --- |
| importedDataTable | DataTable | source instance of System.Data.DataTable |
| isColumnNamesImported | Boolean | specifies whether column names will be imported as first row |
| firstFilledRow | Int32 | specifies zero based number of first row in target table from which import will start, if row with such number(and some previous rows) are absent in target table, they will be created first |
| firstFilledColumn | Int32 | specifies number of first target column in target table , column must be present in target table before start of import |

### See Also

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Imports a DataTable object into the table.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| importedDataTable | DataTable | The DataTable object to be imported. |
| isColumnNamesShown | Boolean | Specifies whether the column names of the source datatable will be imported as first row. |
| firstFilledRow | Int32 | specifies zero based number of first row in target table from which import will start, if row with such number(and some previous rows) are absent in target table, they will be created first |
| firstFilledColumn | Byte | specifies number of first target column in target table , column must be present in target table before start of import |
| maxRows | Int32 | Maximum amount of rows to be imported from source table. |
| maxColumns | Int32 | Maximum amount of columns to be imported from source table. |
| isHtmlSupported | Boolean | Specifies whether the text is html string. |

### See Also

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Imports a DataTable object, but not as whole entity. Only specified rows and columns are imported.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| importedDataTable | DataTable | The DataTable object to be imported. |
| sourceRowList | Int32[] | The array of numbers of rows in source DataTable object that must be imported. List must be not null and must contain only numbers of existing rows, otherwise exception will be thrown. |
| sourceColumnList | Int32[] | The array of numbers of columns in source DataTable object that must be imported. List must be not null and must contain only numbers of existing columns, otherwise exception will be thrown. |
| firstFilledRow | Int32 | The zero based row number of the first cell in targer table from which import will start. If target table does not contain that row, it (and all previous if necessary) will be created |
| firstFilledColumn | Int32 | The zero based column number of the first cell in targer table from which import will start. The target table must contain that column befor import starts, otherwise exception will be thrown. |
| showColumnNamesAsFirstRow | Boolean | Specifies whether the column names of source datatable will be imported as first row. |
| isHtmlSupported | Boolean | Specifies whether the text is html string. |

### See Also

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


