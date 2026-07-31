---
title: "Enum ComparisonMode"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Comparison.ComparisonMode enum. L'enumerazione della modalità di confronto"
type: docs
weight: 3250
url: /it/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

L'enumerazione della modalità di confronto.

```csharp
public enum ComparisonMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Normal | `0` | Modalità normale. Vengono considerati solo gli spazi all'interno dei frammenti di testo (a seconda del modo in cui il documento è generato.) |
| IgnoreSpaces | `1` | Tutti gli spazi sono ignorati. Le modifiche vengono cercate solo nelle parole. |
| ParseSpaces | `2` | La modalità è simile a quella normale, ma tenta di tenere conto della spaziatura visiva tra i frammenti di testo basandosi sulla distanza. Riconoscere il numero di spazi tra i frammenti potrebbe non essere preciso perché dipende molto dal modo in cui i documenti sono generati. Se i documenti sono creati da generatori diversi, potrebbero verificarsi imprecisioni nel confronto degli spazi tra i frammenti di testo. |

### Vedi anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


