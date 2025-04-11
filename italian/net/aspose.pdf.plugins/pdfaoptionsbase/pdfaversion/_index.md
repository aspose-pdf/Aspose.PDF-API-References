---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfAOptionsBase. Ottiene o imposta la versione della norma PDF/A da utilizzare per la validazione o la conversione.
type: docs
weight: 110
url: /it/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## Proprietà PdfAOptionsBase.PdfAVersion

Ottiene o imposta la versione dello standard PDF/A da utilizzare per la validazione o la conversione.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Valore della Proprietà

La versione dello standard PDF/A. Questo può essere uno dei valori dell'enumerazione [`PdfAStandardVersion`](../../pdfastandardversion/).

## Osservazioni

La versione dello standard PDF/A viene utilizzata per determinare il livello di conformità per la validazione e la conversione PDF/A. Se la versione è impostata su Auto, il sistema determinerà automaticamente la versione dello standard PDF/A appropriata per la validazione in base ai metadati del documento. Per il processo di conversione PDF/A, l'Auto predefinisce la versione dello standard PDF/A-1b.

### Vedi Anche

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)