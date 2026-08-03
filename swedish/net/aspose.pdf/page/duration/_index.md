---
title: "Page.Duration"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Page-egenskap. Hämtar eller anger sidans visningstid. Detta är tiden i sekunder som sidan ska visas under en presentation. Returnerar 1 om varaktigheten inte är definierad"
type: docs
weight: 110
url: /sv/net/aspose.pdf/page/duration/
---
## Page.Duration property

Hämtar eller anger sidvisningens varaktighet. Detta är tiden i sekunder som page ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad.

```csharp
public double Duration { get; set; }
```

## Exempel

Exempel visar hur man hämtar sidans varaktighet.

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Se även

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


