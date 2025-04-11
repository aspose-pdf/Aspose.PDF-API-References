---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfExtractor. Получает или устанавливает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения
type: docs
weight: 20
url: /ru/net/aspose.pdf.facades/pdfextractor/endpage/
---
## Свойство PdfExtractor.EndPage

Получает или устанавливает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения.

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

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)