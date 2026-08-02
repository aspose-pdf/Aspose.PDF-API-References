---
title: "PdfExtractor.StartPage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfExtractor. Получает или задаёт начальную страницу в диапазоне страниц, где будет выполнена операция извлечения."
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

Получает или задаёт начальную страницу в диапазоне страниц, где будет выполняться операция извлечения.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


