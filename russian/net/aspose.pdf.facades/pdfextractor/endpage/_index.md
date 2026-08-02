---
title: "PdfExtractor.EndPage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfExtractor. Получает или задаёт конечную страницу в диапазоне страниц, где будет выполнена операция извлечения."
type: docs
weight: 20
url: /ru/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

Получает или задаёт конечную страницу в диапазоне страниц, где будет выполняться операция извлечения.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


