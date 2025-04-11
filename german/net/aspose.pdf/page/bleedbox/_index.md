---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Ruft die Beschnittkante der Seite ab oder setzt sie
type: docs
weight: 70
url: /de/net/aspose.pdf/page/bleedbox/
---
## Page.BleedBox-Eigenschaft

Ruft die Beschnittkante der Seite ab oder setzt sie.

```csharp
public Rectangle BleedBox { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man die Beschnittkante der Seite abruft:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)