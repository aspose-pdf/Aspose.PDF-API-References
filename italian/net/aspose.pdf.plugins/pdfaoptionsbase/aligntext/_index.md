---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfAOptionsBase. Ottiene o imposta un valore che indica se sono necessari mezzi aggiuntivi per preservare l'allineamento del testo durante il processo di conversione PDF/A
type: docs
weight: 10
url: /it/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## Proprietà PdfAOptionsBase.AlignText

Ottiene o imposta un valore che indica se sono necessari mezzi aggiuntivi per preservare l'allineamento del testo durante il processo di conversione PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Valore della Proprietà

`true` se l'allineamento del testo viene modificato e sono necessarie azioni aggiuntive per ripristinarlo; altrimenti, `false`.

## Osservazioni

Quando impostato su `true`, il processo di conversione tenterà di ripristinare i limiti del segmento di testo originale. Per la maggior parte dei documenti non è necessario modificare questa proprietà dal valore predefinito `false`, poiché l'allineamento del testo non cambia durante il processo di conversione predefinito.

### Vedi Anche

* classe [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)