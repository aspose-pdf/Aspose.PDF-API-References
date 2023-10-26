---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Document property. Gets or sets collection of document pages. Note that pages are numbered from 1 in collection
type: docs
weight: 460
url: /net/aspose.pdf/document/pages/
---
## Document.Pages property

Gets or sets collection of document pages. Note that pages are numbered from 1 in collection.

```csharp
public PageCollection Pages { get; }
```

## Examples

Example below demonstrates how to operate with the document pages: How to obtain number of pages and how to obtain rectangle of starting page of the document.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### See Also

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


