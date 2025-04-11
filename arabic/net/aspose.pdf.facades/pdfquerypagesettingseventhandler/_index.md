---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: يمثل الطريقة التي تتعامل مع حدث PdfQueryPageSettings في PdfViewer
type: docs
weight: 4620
url: /ar/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## Delegate PdfQueryPageSettingsEventHandler

يمثل الطريقة التي تتعامل مع حدث [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) في [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sender | Object | مصدر الحدث. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) التي تحتوي على بيانات الحدث. |
| currentPageInfo | PdfPrintPageInfo | معلومات الصفحة المطبوعة حاليًا. |

### انظر أيضًا

* class [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* class [PdfPrintPageInfo](../pdfprintpageinfo/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)