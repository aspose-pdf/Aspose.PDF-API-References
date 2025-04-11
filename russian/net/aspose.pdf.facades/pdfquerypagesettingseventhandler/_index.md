---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: Представляет метод, который обрабатывает событие PdfQueryPageSettings в PdfViewer
type: docs
weight: 4620
url: /ru/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## Делегат PdfQueryPageSettingsEventHandler

Представляет метод, который обрабатывает событие [`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) в [`PdfViewer`](../pdfviewer/).

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | Object | Источник события. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/), который содержит данные события. |
| currentPageInfo | PdfPrintPageInfo | Информация о текущей печатаемой странице. |

### См. также

* класс [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* класс [PdfPrintPageInfo](../pdfprintpageinfo/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)