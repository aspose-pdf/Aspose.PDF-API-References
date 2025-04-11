---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Representa o método que manipula o evento PdfQueryPageSettings de um PdfViewer
type: docs
weight: 4620
url: /pt/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## Delegate PdfQueryPageSettingsEventHandler

Representa o método que manipula o [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) evento de um [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sender | Object | A fonte do evento. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | Um [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) que contém os dados do evento. |
| currentPageInfo | PdfPrintPageInfo | Informações da página atualmente impressa. |

### Veja Também

* class [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* class [PdfPrintPageInfo](../pdfprintpageinfo/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)