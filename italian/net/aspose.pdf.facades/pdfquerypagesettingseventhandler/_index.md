---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Rappresenta il metodo che gestisce l'evento PdfQueryPageSettings di un PdfViewer
type: docs
weight: 4620
url: /it/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## Delegate PdfQueryPageSettingsEventHandler

Rappresenta il metodo che gestisce l'evento [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) di un [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sender | Object | La sorgente dell'evento. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | Un [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) che contiene i dati dell'evento. |
| currentPageInfo | PdfPrintPageInfo | Informazioni sulla pagina attualmente stampata. |

### Vedi Anche

* classe [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* classe [PdfPrintPageInfo](../pdfprintpageinfo/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)