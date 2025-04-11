---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Ruft das Beschnittfeld der Seite ab oder legt es fest
type: docs
weight: 290
url: /de/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox-Eigenschaft

Ruft das Beschnittfeld der Seite ab oder legt es fest.

```csharp
public Rectangle TrimBox { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man das Beschnittfeld der Seite abruft:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)