---
title: "Table.ImportArray"
linktitle: "ImportArray"
articleTitle: "ImportArray"
second_title: "Aspose.PDF for .NET"
description: "Imports one-dimensional array of data into table. Import goes one cell per each array's item and starts from row and column defined in parameters. During imp..."
type: docs
weight: 50
url: "/net/aspose.pdf/table/importarray/"
product_version: "26.9.0"
---
## ImportArray(object[], int, int, bool) {#importarray}

Imports one-dimensional array of data into table. Import goes one cell per each array's item and
 starts from row and column defined in parameters. During import, if detected that necessary rows
 are still absent(i.e. target table is too small to absorb all data), necessary rows will be created

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, bool isLeftColumnsFilled)
```

| Parameter | Type | Description |
| --- | --- | --- |
| importedArray | object[] | imported data, nulls will be imported as empty strings |
| firstFilledRow | int | define number of first target row in target table from wich import will start.
 If amount of rows in target table less then required, missing rows will be created first. |
| firstFilledColumn | int | specifies number of first target column in target table , column must be present in target table before start of import |
| isLeftColumnsFilled | bool | If 'isLeftColumnsFilled'=false, then in second and all subsequent filled rows cells that are on the left hand from
 firstFilledColumn will be skipped |

### See Also

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

