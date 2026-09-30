---
title: "XFA.Item"
linktitle: "Item"
articleTitle: "Item"
second_title: "Aspose.PDF for .NET API Reference"
description: "XFA property. Gets of sets data node value according path."
type: docs
weight: 90
url: "/net/aspose.pdf.forms/xfa/item/"
product_version: "26.9.0"
---
## XFA indexer

Gets of sets data node value according *path*.

```csharp
public string this[string path] { get; set; }
```

| Parameter | Description |
| --- | --- |
| path | Data node path, e.g. form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. 
 Be sure to include indices even if data contains only single occurences of each nodes, 
 i.e. write node1[0].node2[0]... instead of node1.node2... |

### Return Value

Data node value.

### See Also

* class [XFA](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

