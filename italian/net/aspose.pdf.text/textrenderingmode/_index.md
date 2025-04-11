---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: La modalità di rendering del testo Tmode determina semostrare il testo dovra causare contorni degli stili di carattere a essere riempiti, usati come confine di taglio, o una combinazione di questi tre.
type: docs
weight: 11000
url: /it/net/aspose.pdf.text/textrenderingmode/
---
## Enumerazione TextRenderingMode

La modalità di rendering del testo, Tmode, determina se la visualizzazione del testo deve causare il tracciamento dei contorni dei glifi, il riempimento, l'uso come confine di ritaglio o una combinazione di questi tre.

```csharp
public enum TextRenderingMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| FillText | `0` | Riempire il testo. |
| StrokeText | `1` | Tracciare il testo. |
| FillThenStrokeText | `2` | Riempire, quindi tracciare il testo. |
| Invisible | `3` | Né riempire né tracciare il testo (invisibile). |
| FillTextAndAddPathToClipping | `4` | Riempire il testo e aggiungere al percorso per il ritaglio (vedi 9.3.6, "Modalità di Rendering del Testo"). |
| StrokeTextAndAddPathToClipping | `5` | Tracciare il testo e aggiungere al percorso per il ritaglio. |
| FillThenStrokeTextAndAddPathToClipping | `6` | Riempire, quindi tracciare il testo e aggiungere al percorso per il ritaglio. |
| AddPathToClipping | `7` | Aggiungere il testo al percorso per il ritaglio. |

### Vedi Anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)