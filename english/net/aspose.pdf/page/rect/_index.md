---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Page property. Gets or sets rectangle of the page. For get page crop box is returned if specified otherwise page media box is returned. For set page media box always set. Please note that this property dont consider page rotation. To get page rectangle considering rotation please use ActualRect
type: docs
weight: 230
url: /net/aspose.pdf/page/rect/
---
## Page.Rect property

Gets or sets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Examples

Example demonstrates how to get page rectangle:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### See Also

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


