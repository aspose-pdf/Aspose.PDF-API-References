---
title: "Page.Rect"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Page-egenskap. Hämtar eller anger rektangeln för sidan. Vid hämtning returneras sidans beskärningsruta om den är angiven, annars returneras sidans mediabox. Vid sättning sätts alltid mediaboxen. Observera att denna egenskap inte tar hänsyn till sidrotation. För att få sidrektangeln med rotation, använd ActualRect."
type: docs
weight: 230
url: /sv/net/aspose.pdf/page/rect/
---
## Page.Rect property

Hämtar eller anger rektangel för page. Vid hämtning: page‑beskärningsruta returneras om angiven, annars returneras page‑mediabox. Vid angivning: page‑mediabox sätts alltid. Observera att denna egenskap inte beaktar page‑rotation. För att hämta page‑rektangel med rotation, använd ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Exempel

Exempel visar hur man hämtar sidrektangeln:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Se även

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


