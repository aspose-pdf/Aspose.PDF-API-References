---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Ruft das Kunstfeld der Seite ab oder setzt es
type: docs
weight: 30
url: /de/net/aspose.pdf/page/artbox/
---
## Seite.ArtBox-Eigenschaft

Ruft das Kunstfeld der Seite ab oder setzt es.

```csharp
public Rectangle ArtBox { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man das Kunstfeld der Seite abruft:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### Siehe auch

* Klasse [Rechteck](../../rectangle/)
* Klasse [Seite](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)