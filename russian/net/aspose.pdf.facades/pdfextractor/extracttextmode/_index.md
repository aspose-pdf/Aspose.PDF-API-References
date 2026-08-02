---
title: "PdfExtractor.ExtractTextMode"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfExtractor. Устанавливает режим для результата извлечения текста."
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Устанавливает режим результата извлечения текста.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 — режим чистого текста, 1 — режим необработанного порядка. По умолчанию 0.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


