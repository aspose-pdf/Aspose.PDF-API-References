---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Stellt die Methode dar, die das PdfQueryPageSettings-Ereignis eines PdfViewers behandelt
type: docs
weight: 4620
url: /de/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler-Delegat

Stellt die Methode dar, die das [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) Ereignis eines [`PdfViewer`](../pdfviewer/) behandelt.

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | Objekt | Die Quelle des Ereignisses. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | Ein [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/), das die Ereignisdaten enthält. |
| currentPageInfo | PdfPrintPageInfo | Informationen zur aktuell gedruckten Seite. |

### Siehe auch

* Klasse [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* Klasse [PdfPrintPageInfo](../pdfprintpageinfo/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)