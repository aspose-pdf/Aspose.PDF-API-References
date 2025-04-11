---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: 表方法。将 DataView 对象的数据导入表中
type: docs
weight: 270
url: /zh/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView 方法

将 DataView 对象的数据导入表中。

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceDataView | DataView | 要导入的 DataView 对象。 |
| isColumnNamesImported | Boolean | 指示列名是否将作为第一行导入。 |
| firstFilledRow | Int32 | 目标表中导入开始的第一个单元格的零基行号。如果目标表不包含该行，则将创建该行（如有必要，还会创建所有之前的行） |
| firstFilledColumn | Int32 | 目标表中导入开始的第一个单元格的零基列号。目标表必须在导入开始之前包含该列，否则将抛出异常。 |
| maxRows | Int32 | 从源 DataView 导入的最大行数。 |
| maxColumns | Int32 | 从源 DataView 导入的最大列数。 |

### 另请参阅

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)