---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Page-egenskap. Hämtar eller ställer in rektangeln för sidan. För att hämta: sidans beskärningsruta returneras om den anges, annars returneras sidans mediaruta. För att ställa in: sidans mediaruta ställs alltid in. Observera att denna egenskap inte tar hänsyn till sidrotation. För att få sidrektangeln med hänsyn till rotation, vänligen använd ActualRect
type: docs
weight: 230
url: /sv/net/aspose.pdf/page/rect/
---
## Page.Rect-egenskap

Hämtar eller ställer in rektangeln för sidan. För att hämta: sidans beskärningsruta returneras om den anges, annars returneras sidans mediaruta. För att ställa in: sidans mediaruta ställs alltid in. Observera att denna egenskap inte tar hänsyn till sidrotation. För att få sidrektangeln med hänsyn till rotation, vänligen använd ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Exempel

Exemplet visar hur man hämtar sidrektangeln:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Page](../)
* namnrum [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)