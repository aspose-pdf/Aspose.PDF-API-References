---
title: "OptimizationOptions.LinkDuplicateStreams"
linktitle: "LinkDuplicateStreams"
articleTitle: "LinkDuplicateStreams"
second_title: "Aspose.PDF for .NET API Reference"
description: "OptimizationOptions property. If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equa..."
type: docs
weight: 50
url: "/net/aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/"
product_version: "26.9"
---
## OptimizationOptions.LinkDuplicateStreams property

If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. 
 This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times).

```csharp
public bool LinkDuplicateStreams { get; set; }
```

### See Also

* class [OptimizationOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)

