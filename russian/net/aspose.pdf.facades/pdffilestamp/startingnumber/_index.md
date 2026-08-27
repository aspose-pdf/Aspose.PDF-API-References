---
title: "PdfFileStamp.StartingNumber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfFileStamp. Получает или задает начальный номер первой страницы во входном файле. Последующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлен в 100, страницы документа будут иметь номера 100 101 102."
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

Получает или задает начальный номер первой страницы во входном файле. Последующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлено в 100, страницы документа будут иметь номера 100, 101, 102...

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

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


