---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Sidans egenskap. Hämtar eller ställer in beskärningsrutan för sidan
type: docs
weight: 100
url: /sv/net/aspose.pdf/page/cropbox/
---
## Page.CropBox-egenskap

Hämtar eller ställer in beskärningsrutan för sidan.

```csharp
public Rectangle CropBox { get; set; }
```

## Exempel

Exemplet visar hur man hämtar beskärningsrutan för sidan:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)