---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ComparisonMode di Aspose.Pdf.Comparison. L'enumerazione della modalità di confronto
type: docs
weight: 3140
url: /it/net/aspose.pdf.comparison/comparisonmode/
---
## Enumerazione ComparisonMode

L'enumerazione della modalità di confronto.

```csharp
public enum ComparisonMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Normale | `0` | Modalità normale. Vengono presi in considerazione solo gli spazi all'interno dei frammenti di testo (a seconda del modo in cui viene generato il documento.) |
| IgnoraSpazi | `1` | Tutti gli spazi vengono ignorati. Le modifiche vengono cercate solo nelle parole. |
| AnalizzaSpazi | `2` | La modalità è simile a normale, ma cerca di tenere conto dello spazio visivo tra i frammenti di testo in base alla distanza. Riconoscere il numero di spazi tra i frammenti potrebbe non essere accurato perché dipende molto da come vengono generati i documenti. Se i documenti sono creati da generatori diversi, potrebbero esserci imprecisioni nel confrontare gli spazi tra i frammenti di testo. |

### Vedi Anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)