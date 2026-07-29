---
title: "XFA.Item"
second_title: "Aspose.PDF for .NET API 参考"
description: "XFA 属性。根据路径获取或设置数据节点值"
type: docs
weight: 50
url: /zh/net/aspose.pdf.forms/xfa/item/
---
## XFA indexer

根据 *path* 获取或设置数据节点的值。

```csharp
public string this[string path] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 路径 | 数据节点路径，例如 form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]。即使每个节点只有单个实例，也必须包含索引，即写成 node1[0].node2[0]... 而不是 node1.node2... |

### 返回值

数据节点值。

### 另请参见

* class [XFA](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


