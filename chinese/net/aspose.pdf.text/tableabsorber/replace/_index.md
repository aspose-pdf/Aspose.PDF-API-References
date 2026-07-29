---
title: "TableAbsorber.Replace"
second_title: "Aspose.PDF for .NET API 参考"
description: "TableAbsorber 方法。将页面上的 AbsorbedTable 替换为 Table。"
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace method

在页面上将 [`AbsorbedTable`](../../absorbedtable/) 替换为 [`Table`](../../../aspose.pdf/table/)。

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | 页面 | Pdf 文档页面对象。 |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) 要替换的。 |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) 用于替换旧表格。 |

## 备注

请注意，它会更改 TableList 集合。如果在循环中删除/替换表格，请使用 TableList 集合的副本。

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [AbsorbedTable](../../absorbedtable/)
* class [Table](../../../aspose.pdf/table/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


