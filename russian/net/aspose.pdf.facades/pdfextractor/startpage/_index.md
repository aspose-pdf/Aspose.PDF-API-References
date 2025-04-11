---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfExtractor. Получает или устанавливает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdfextractor/startpage/
---
## Свойство PdfExtractor.StartPage

Получает или устанавливает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения.

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

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)