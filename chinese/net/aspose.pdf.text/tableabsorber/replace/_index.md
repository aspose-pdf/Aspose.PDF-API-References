---
title: Replace
second_title: Aspose.PDF for .NET API 参考
description: 替换一个AbsorbedTableaspose.pdf.text/absorbedtable和Tableaspose.pdf/table在页面上
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace method

替换一个[`AbsorbedTable`](../../absorbedtable)和[`Table`](../../../aspose.pdf/table)在页面上。

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | Pdf pocument 页面对象。 |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable)将被替代。 |
| newTable | Table | [`Table`](../../../aspose.pdf/table)替换旧表。 |

### 评论

请考虑它会更改 TableList 集合。如果在循环中删除/替换表，请使用 TableList 集合的副本。

### 也可以看看

* class [Page](../../../aspose.pdf/page)
* class [AbsorbedTable](../../absorbedtable)
* class [Table](../../../aspose.pdf/table)
* class [TableAbsorber](../../tableabsorber)
* 命名空间 [Aspose.Pdf.Text](../../tableabsorber)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->