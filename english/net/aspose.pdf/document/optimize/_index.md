---
title: "Document.Optimize"
linktitle: "Optimize"
articleTitle: "Optimize"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Linearize the document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as q..."
type: docs
weight: 670
url: "/net/aspose.pdf/document/optimize/"
product_version: "26.9.0"
---
## Optimize() {#optimize}

Linearize the document in order to
 - open the first page as quickly as possible;
 - display next page or follow by link to the next page as quickly as possible;
 - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first);
 - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed.
 Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure,
 call then Save to get optimized document.

```csharp
public void Optimize()
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

