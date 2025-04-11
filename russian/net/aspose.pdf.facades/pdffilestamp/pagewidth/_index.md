---
title: PdfFileStamp.PageWidth
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfFileStamp. Получает ширину первой страницы во входном файле
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdffilestamp/pagewidth/
---
## Свойство PdfFileStamp.PageWidth

Получает ширину первой страницы во входном файле.

```csharp
public float PageWidth { get; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Width = " + fileStamp.PageWidth);
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)