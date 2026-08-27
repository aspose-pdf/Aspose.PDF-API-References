---
title: "Klass Id"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Id-klass. Representerar filidentifieringsstruktur"
type: docs
weight: 5980
url: /sv/net/aspose.pdf/id/
---
## Id class

Representerar filidentifieringsstruktur.

```csharp
public class Id
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Ändrar identifieraren baserat på dokumentets innehåll vid den tidpunkt den senast uppdaterades. |
| [Original](../../aspose.pdf/id/original/) { get; } | Permanent identifierare baserad på dokumentets innehåll när det ursprungligen skapades. |

## Exempel

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


