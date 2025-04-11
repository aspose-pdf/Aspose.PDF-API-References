---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Seitenattribut. Erhält die angezeigte Dauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während der Präsentation angezeigt werden soll. Gibt 1 zurück, wenn die Dauer nicht definiert ist.
type: docs
weight: 110
url: /de/net/aspose.pdf/page/duration/
---
## Page.Duration-Eigenschaft

Erhält die angezeigte Dauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während der Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist.

```csharp
public double Duration { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man die Seiten-Dauer erhält.

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Siehe auch

* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)