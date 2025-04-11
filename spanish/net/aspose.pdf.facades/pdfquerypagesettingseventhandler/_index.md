---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Representa el método que maneja el evento PdfQueryPageSettings de un PdfViewer
type: docs
weight: 4620
url: /es/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## Delegado PdfQueryPageSettingsEventHandler

Representa el método que maneja el evento [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) de un [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sender | Object | La fuente del evento. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | Un [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) que contiene los datos del evento. |
| currentPageInfo | PdfPrintPageInfo | Información de la página actualmente impresa. |

### Ver También

* clase [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* clase [PdfPrintPageInfo](../pdfprintpageinfo/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../)