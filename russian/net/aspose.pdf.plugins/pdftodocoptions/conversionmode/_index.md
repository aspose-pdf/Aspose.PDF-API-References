---
title: "PdfToDocOptions.ConversionMode"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfToDocOptions. Позволяет контролировать, как PDF‑документ преобразуется в документ обработки текста."
type: docs
weight: 20
url: /ru/net/aspose.pdf.plugins/pdftodocoptions/conversionmode/
---
## PdfToDocOptions.ConversionMode property

Позволяет управлять тем, как PDF‑документ конвертируется в документ обработки текста.

```csharp
public ConversionMode ConversionMode { get; set; }
```

## Примечания

Используйте режим TextBox, когда полученный документ не будет сильно редактироваться дальше. TextBox‑ы легко изменять, если требуется небольшое количество правок.

Используйте режим Flow, когда выходной документ требует дальнейшего редактирования. Абзацы и строки текста в режиме Flow позволяют легко изменять текст, но неподдерживаемые объекты форматирования будут выглядеть хуже, чем в режиме TextBox.

### См. также

* enum [ConversionMode](../../conversionmode/)
* class [PdfToDocOptions](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


