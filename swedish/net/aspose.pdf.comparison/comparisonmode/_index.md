---
title: "Enum ComparisonMode"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.ComparisonMode enum. Jämförelselägets uppräkning"
type: docs
weight: 3250
url: /sv/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

Jämförelseläges‑enumerationen.

```csharp
public enum ComparisonMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Normal | `0` | Normalt läge. Endast mellanslag inom textfragment beaktas (beroende på hur dokumentet genereras.) |
| IgnoreSpaces | `1` | Alla mellanslag ignoreras. Ändringar söks endast i ord. |
| ParseSpaces | `2` | Läget liknar det normala, men försöker ta hänsyn till visuellt avstånd mellan textfragment baserat på avstånd. Att känna igen antalet mellanslag mellan fragment kan vara inexakt eftersom det starkt beror på hur dokumenten genereras. Om dokument skapas av olika generatorer kan det finnas felaktigheter i jämförelsen av mellanslag mellan textfragment. |

### Se även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


