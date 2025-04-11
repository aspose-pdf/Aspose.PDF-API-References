---
title: PdfFileStamp.PageHeight
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfFileStamp. Получает высоту первой страницы в исходном файле
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdffilestamp/pageheight/
---
## Свойство PdfFileStamp.PageHeight

Получает высоту первой страницы в исходном файле.

```csharp
public float PageHeight { get; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Height = " + fileStamp.PageHeight);
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)