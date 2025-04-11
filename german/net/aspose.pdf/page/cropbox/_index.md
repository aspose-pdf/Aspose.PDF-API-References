---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Ruft das Zuschneidefeld der Seite ab oder legt es fest
type: docs
weight: 100
url: /de/net/aspose.pdf/page/cropbox/
---
## Page.CropBox-Eigenschaft

Ruft das Zuschneidefeld der Seite ab oder legt es fest.

```csharp
public Rectangle CropBox { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man das Zuschneidefeld der Seite abruft:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)