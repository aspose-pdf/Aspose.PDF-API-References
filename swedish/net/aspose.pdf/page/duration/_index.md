---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Sidans egenskap. Hämtar eller ställer in sidans visningstid. Detta är tiden i sekunder som sidan ska visas under presentationen. Returnerar 1 om varaktigheten inte är definierad
type: docs
weight: 110
url: /sv/net/aspose.pdf/page/duration/
---
## Page.Duration egenskap

Hämtar eller ställer in sidans visningstid. Detta är tiden i sekunder som sidan ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad.

```csharp
public double Duration { get; set; }
```

## Exempel

Exemplet visar hur man hämtar sidans varaktighet

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Se Även

* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)