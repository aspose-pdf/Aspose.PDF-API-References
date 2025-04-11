---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id klass. Representerar filidentifierarens struktur
type: docs
weight: 5850
url: /sv/net/aspose.pdf/id/
---
## Id klass

Representerar filidentifierarens struktur.

```csharp
public class Id
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Modifierad](../../aspose.pdf/id/modified/) { get; } | Ändrar identifieraren baserat på dokumentets innehåll vid den tidpunkt det senast uppdaterades. |
| [Original](../../aspose.pdf/id/original/) { get; } | Permanent identifierare baserat på dokumentets innehåll vid den tidpunkt det ursprungligen skapades. |

## Exempel

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)