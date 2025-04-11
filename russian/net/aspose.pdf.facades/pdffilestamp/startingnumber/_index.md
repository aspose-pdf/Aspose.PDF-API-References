---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfFileStamp. Получает или устанавливает начальный номер для первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлен на 100, страницы документа будут иметь номера 100, 101, 102
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## Свойство PdfFileStamp.StartingNumber

Получает или устанавливает начальный номер для первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлен на 100, страницы документа будут иметь номера 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### См. также

* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)