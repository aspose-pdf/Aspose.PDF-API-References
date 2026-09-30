---
title: "ParagraphAbsorber.SectionsSearchDepth"
linktitle: "SectionsSearchDepth"
articleTitle: "SectionsSearchDepth"
second_title: "Aspose.PDF for .NET API Reference"
description: "ParagraphAbsorber property. Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Defau..."
type: docs
weight: 80
url: "/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/"
product_version: "26.9.0"
---
## ParagraphAbsorber.SectionsSearchDepth property

Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed.
 Default search depth is 3.
 It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns).

Increasing of this value may lead to minor decreasing performance with no visible changes in search result.
 Decreasing of this value may lead to incorrect determination of paragraphs in sections.
 We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure.

```csharp
public int SectionsSearchDepth { get; set; }
```

### See Also

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

