---
title: PdfViewer.PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfViewer. Печатает Pdf документ с диалогом настройки. Выберите принтер с помощью диалога
type: docs
weight: 340
url: /ru/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## Метод PdfViewer.PrintDocumentWithSetup

Печатает Pdf документ с диалогом настройки. Выберите принтер с помощью диалога.

```csharp
public void PrintDocumentWithSetup()
```

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### См. также

* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)