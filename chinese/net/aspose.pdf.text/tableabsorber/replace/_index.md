---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber 方法。用页面上的 Table 替换 AbsorbedTable
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace 方法

用 [`Table`](../../../aspose.pdf/table/) 替换页面上的 [`AbsorbedTable`](../../absorbedtable/)。

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | Pdf 文档页面对象。 |
| oldTable | AbsorbedTable | 要被替换的 [`AbsorbedTable`](../../absorbedtable/)。 |
| newTable | Table | 用于替换旧表的 [`Table`](../../../aspose.pdf/table/)。 |

## 备注

请注意，它会更改 TableList 集合。如果在循环中移除/替换表，请使用 TableList 集合的副本。

### 另见

* 类 [Page](../../../aspose.pdf/page/)
* 类 [AbsorbedTable](../../absorbedtable/)
* 类 [Table](../../../aspose.pdf/table/)
* 类 [TableAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)