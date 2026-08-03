---
title: "Document.Pages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-egenskap. Hämtar eller anger en samling av dokumentets sidor. Observera att sidorna numreras från 1 i samlingen"
type: docs
weight: 490
url: /sv/net/aspose.pdf/document/pages/
---
## Document.Pages property

Hämtar eller anger samling av dokumentsidor. Observera att sidor numreras från 1 i samlingen.

```csharp
public PageCollection Pages { get; }
```

## Exempel

Exemplet nedan visar hur man arbetar med dokumentets sidor: Hur man får antalet sidor och hur man får rektangeln för den första sidan i dokumentet.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Se även

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


