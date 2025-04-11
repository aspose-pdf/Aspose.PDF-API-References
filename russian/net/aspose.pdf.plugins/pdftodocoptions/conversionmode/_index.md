---
title: PdfToDocOptions.ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfToDocOptions. Позволяет контролировать, как PDF-документ преобразуется в документ обработки текста
type: docs
weight: 20
url: /ru/net/aspose.pdf.plugins/pdftodocoptions/conversionmode/
---
## Свойство PdfToDocOptions.ConversionMode

Позволяет контролировать, как PDF-документ преобразуется в документ обработки текста.

```csharp
public ConversionMode ConversionMode { get; set; }
```

## Замечания

Используйте режим TextBox, когда итоговый документ не будет сильно редактироваться. Текстовые поля легко модифицировать, когда не нужно много изменений.

Используйте режим Flow, когда выходной документ требует дальнейшего редактирования. Параграфы и текстовые строки в режиме Flow позволяют легко модифицировать текст, но неподдерживаемые объекты форматирования будут выглядеть хуже, чем в режиме TextBox.

### См. также

* enum [ConversionMode](../../conversionmode/)
* class [PdfToDocOptions](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)