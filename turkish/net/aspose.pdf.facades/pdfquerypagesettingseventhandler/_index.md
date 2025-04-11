---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer'ın PdfQueryPageSettings olayını işleyen yöntemi temsil eder
type: docs
weight: 4620
url: /tr/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler delegesi

[`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) olayını [`PdfViewer`](../pdfviewer/) için işleyen yöntemi temsil eder.

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sender | Object | Olayın kaynağı. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | Olay verilerini içeren bir [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/). |
| currentPageInfo | PdfPrintPageInfo | Şu anda yazdırılan sayfa bilgisi. |

### Ayrıca Bakınız

* sınıf [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* sınıf [PdfPrintPageInfo](../pdfprintpageinfo/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)