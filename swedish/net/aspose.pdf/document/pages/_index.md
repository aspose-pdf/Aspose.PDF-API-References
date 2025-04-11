---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Dokumentegenskap. Hämtar eller ställer in samlingen av dokument sidor. Observera att sidor numreras från 1 i samlingen
type: docs
weight: 470
url: /sv/net/aspose.pdf/document/pages/
---
## Document.Pages egenskap

Hämtar eller ställer in samlingen av dokument sidor. Observera att sidor numreras från 1 i samlingen.

```csharp
public PageCollection Pages { get; }
```

## Exempel

Exemplet nedan visar hur man arbetar med dokument sidor: Hur man får antalet sidor och hur man får rektangeln för den första sidan av dokumentet.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Se Även

* klass [PageCollection](../../pagecollection/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)