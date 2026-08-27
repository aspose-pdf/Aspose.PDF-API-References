---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfAOptionsBase. Получает или задает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса преобразования PDF/A."
type: docs
weight: 30
url: /ru/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

Получает или задает стратегию удаления шрифтов для уменьшения размера выходного файла во время процесса конвертации PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

Стратегия удаления шрифтов. Это может быть одно из значений перечисления [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). По умолчанию используется комбинация SubsetFonts и RemoveDuplicatedFonts.

## Примечания

Это свойство позволяет управлять обработкой шрифтов во время процесса преобразования. Вы можете выбрать удаление дублированных шрифтов, удаление похожих шрифтов с разной шириной или подмножество шрифтов.

### См. также

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


