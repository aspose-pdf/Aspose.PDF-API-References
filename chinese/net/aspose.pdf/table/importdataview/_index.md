---
title: ImportDataView
second_title: Aspose.PDF for .NET API 参考
description: 导入一个DataView对象的数据到表中
type: docs
weight: 270
url: /zh/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

导入一个DataView对象的数据到表中。

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sourceDataView | DataView | 这DataView要导入的对象。 |
| isColumnNamesImported | Boolean | 指示列名是否将 作为第一行导入。 |
| firstFilledRow | Int32 | 从零开始导入的目标表中第一个单元格的行号。 如果目标表不包含该行，则将创建它（以及所有先前的行，如有必要） |
| firstFilledColumn | Int32 | 从零开始导入的目标表中第一个单元格的列号。 在导入开始前，目标表必须包含该列，否则会抛出异常。 |
| maxRows | Int32 | 要从源数据视图导入的最大行数。 |
| maxColumns | Int32 | 要从源数据视图导入的最大列数。 |

### 也可以看看

* class [Table](../../table)
* 命名空间 [Aspose.Pdf](../../table)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->