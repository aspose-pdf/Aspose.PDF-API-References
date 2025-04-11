---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id-Klasse. Stellt die Struktur des Dateiidentifikators dar
type: docs
weight: 5850
url: /de/net/aspose.pdf/id/
---
## Id-Klasse

Stellt die Struktur des Dateiidentifikators dar.

```csharp
public class Id
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Änderungsidentifikator basierend auf dem Inhalt des Dokuments zum Zeitpunkt der letzten Aktualisierung. |
| [Original](../../aspose.pdf/id/original/) { get; } | Permanenter Identifikator basierend auf dem Inhalt des Dokuments zum Zeitpunkt der ursprünglichen Erstellung. |

## Beispiele

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)