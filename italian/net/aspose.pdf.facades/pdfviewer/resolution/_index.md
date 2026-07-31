---
title: "PdfViewer.Resolution"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà PdfViewer. Ottiene o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150"
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

Ottiene o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150.

```csharp
public int Resolution { get; set; }
```

## Osservazioni

Questa proprietà modifica la risoluzione dell'immagine nei flussi di conversione da pagina a immagine: quando [`PrintAsImage`](../printasimage/) è impostato su `true`, o quando il metodo [`DecodePage`](../decodepage/) o [`DecodeAllPages`](../decodeallpages/) viene chiamato. Per impostare una risoluzione della stampante per la stampa diretta su stampante, utilizzare la proprietà [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) nella classe [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Vedi anche

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


