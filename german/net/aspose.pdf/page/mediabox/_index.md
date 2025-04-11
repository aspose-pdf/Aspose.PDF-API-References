---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Ruft das Medienfeld der Seite ab oder legt es fest
type: docs
weight: 180
url: /de/net/aspose.pdf/page/mediabox/
---
## Page.MediaBox-Eigenschaft

Ruft das Medienfeld der Seite ab oder legt es fest.

```csharp
public Rectangle MediaBox { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man das Medienfeld der Seite abruft:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)