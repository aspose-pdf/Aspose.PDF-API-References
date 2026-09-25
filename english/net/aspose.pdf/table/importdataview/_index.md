---
title: "Table.ImportDataView"
linktitle: "ImportDataView"
articleTitle: "ImportDataView"
second_title: "Aspose.PDF for .NET API Reference"
description: "Table method. Imports a DataView object's data into the table."
type: docs
weight: 90
url: "/net/aspose.pdf/table/importdataview/"
product_version: "26.9.0"
---
## ImportDataView(DataView, bool, int, int, int, int) {#importdataview}

Imports a `DataView` object's data into the table.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceDataView | DataView | The <see cref="T:System.Data.DataView" /> object to be imported. |
| isColumnNamesImported | bool | Indicates whether the column names will be 
 imported as first row. |
| firstFilledRow | int | The zero based row number of the first cell in targer table from which import will start.
 If target table does not contain that row, it (and all previous if necessary) will be created |
| firstFilledColumn | int | The zero based column number of the first cell in targer table from which import will start. 
 The target table must contain that column before import starts, otherwise exception will be thrown. |
| maxRows | int | Maximum amount of rows to be imported from source dataview. |
| maxColumns | int | Maximum columns to be imported from source dataview. |

### See Also

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

