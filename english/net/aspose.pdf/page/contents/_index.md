---
title: "Page.Contents"
linktitle: "Contents"
articleTitle: "Contents"
second_title: "Aspose.PDF for .NET API Reference"
description: "Page property. Gets collection of operators in the content stream of the page. OperatorCollection"
type: docs
weight: 480
url: "/net/aspose.pdf/page/contents/"
product_version: "26.9"
---
## Page.Contents property

Gets collection of operators in the content stream of the page.
 [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Examples

Example is demonstrates how to scan operators stream of page.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### See Also

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

