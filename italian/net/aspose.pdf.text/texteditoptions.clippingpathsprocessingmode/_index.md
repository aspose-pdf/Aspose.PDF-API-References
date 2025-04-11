---
title: Enum TextEditOptions.ClippingPathsProcessingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsClippingPathsProcessingMode enum. Clipping path processing modes
type: docs
weight: 10830
url: /it/net/aspose.pdf.text/texteditoptions.clippingpathsprocessingmode/
---
## Enumerazione TextEditOptions.ClippingPathsProcessingMode

Modalità di elaborazione dei percorsi di ritaglio

```csharp
public enum ClippingPathsProcessingMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| KeepIntact | `0` | Mantiene i percorsi di ritaglio del layout originale della pagina. (Predefinito) |
| Expand | `1` | Il percorso di ritaglio originale sarà espanso nel caso in cui il testo modificato richieda più spazio. |
| Remove | `2` | Il percorso di ritaglio originale sarà rimosso nel caso in cui il testo modificato richieda più spazio. Attenzione: Poiché i percorsi di ritaglio possono interagire tra loro, la loro rimozione può portare a risultati imprevisti nel layout della pagina. |

### Vedi Anche

* classe [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)