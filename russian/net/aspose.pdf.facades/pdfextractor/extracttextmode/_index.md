---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfExtractor. Устанавливает режим для результата извлечения текста
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## Свойство PdfExtractor.ExtractTextMode

Устанавливает режим для результата извлечения текста.

```csharp
public int ExtractTextMode { get; set; }
```

### Значение свойства

0 — это режим чистого текста, а 1 — режим сырого порядка. По умолчанию 0.

## Примеры

Пример демонстрирует использование свойства `ExtractTextMode` в сценарии извлечения текста.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)