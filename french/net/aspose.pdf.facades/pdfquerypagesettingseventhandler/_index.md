---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Représente la méthode qui gère l'événement PdfQueryPageSettings d'un PdfViewer
type: docs
weight: 4620
url: /fr/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## Délégué PdfQueryPageSettingsEventHandler

Représente la méthode qui gère l'événement [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) d'un [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sender | Object | La source de l'événement. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | Un [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) qui contient les données de l'événement. |
| currentPageInfo | PdfPrintPageInfo | Informations sur la page actuellement imprimée. |

### Voir aussi

* classe [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* classe [PdfPrintPageInfo](../pdfprintpageinfo/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)