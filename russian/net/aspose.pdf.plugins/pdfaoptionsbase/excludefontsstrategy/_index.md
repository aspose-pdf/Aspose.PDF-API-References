---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfAOptionsBase. Получает или устанавливает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A
type: docs
weight: 30
url: /ru/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## Свойство PdfAOptionsBase.ExcludeFontsStrategy

Получает или устанавливает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Значение свойства

Стратегия удаления шрифтов. Это может быть одно из значений перечисления [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). По умолчанию используется комбинация SubsetFonts и RemoveDuplicatedFonts.

## Замечания

Это свойство позволяет вам контролировать, как обрабатываются шрифты во время процесса конвертации. Вы можете выбрать удаление дублированных шрифтов, удаление похожих шрифтов с разной шириной или подмножество шрифтов.

### См. также

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)