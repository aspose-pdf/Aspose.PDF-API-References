---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfViewer. Печатает Pdf документ с использованием принтера по умолчанию
type: docs
weight: 320
url: /ru/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## Метод PdfViewer.PrintDocument

Печатает Pdf документ с использованием принтера по умолчанию.

```csharp
public void PrintDocument()
```

## Примеры

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         'print the file with adjusted size
iewer.AutoRotate = true;         'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### См. также

* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)