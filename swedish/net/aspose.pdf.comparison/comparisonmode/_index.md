---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode enum. Enumeration för jämförelseläge
type: docs
weight: 3140
url: /sv/net/aspose.pdf.comparison/comparisonmode/
---
## Enumeration för ComparisonMode

Enumeration för jämförelseläge.

```csharp
public enum ComparisonMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Normal | `0` | Normalt läge. Endast mellanslag inom textfragment beaktas (beroende på hur dokumentet genereras.) |
| IgnoreSpaces | `1` | Alla mellanslag ignoreras. Ändringar söks endast i ord. |
| ParseSpaces | `2` | Läge är liknande normalt, men försöker ta hänsyn till visuell avstånd mellan textfragment baserat på avstånd. Att känna igen antalet mellanslag mellan fragment kan vara oexakt eftersom detta i hög grad beror på hur dokumenten genereras. Om dokument skapas av olika generatorer kan det finnas oegentligheter i att jämföra mellanslag mellan textfragment. |

### Se Även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)