---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di PdfViewer. Ottiene o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfviewer/resolution/
---
## Proprietà PdfViewer.Resolution

Ottiene o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150.

```csharp
public int Resolution { get; set; }
```

## Osservazioni

Questa proprietà cambia la risoluzione dell'immagine nei flussi di conversione da pagina a immagine: quando [`PrintAsImage`](../printasimage/) è impostato su `true`, o quando viene chiamato il metodo [`DecodePage`](../decodepage/) o [`DecodeAllPages`](../decodeallpages/). Per impostare una risoluzione della stampante per la stampa diretta su una stampante, utilizzare la proprietà [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) nella classe [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Vedi Anche

* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)