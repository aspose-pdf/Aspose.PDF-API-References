---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Representerar metoden som hanterar PdfQueryPageSettings-händelsen för en PdfViewer
type: docs
weight: 4620
url: /sv/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler-delegat

Representerar metoden som hanterar [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) händelsen för en [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | Objekt | Källan till händelsen. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | En [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) som innehåller händelsedata. |
| currentPageInfo | PdfPrintPageInfo | För närvarande utskriven sidinformation. |

### Se Även

* klass [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* klass [PdfPrintPageInfo](../pdfprintpageinfo/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)