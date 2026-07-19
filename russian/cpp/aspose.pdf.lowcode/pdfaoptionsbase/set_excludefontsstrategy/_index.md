---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase::set_ExcludeFontsStrategy метод"
linktitle: "set_ExcludeFontsStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase::set_ExcludeFontsStrategy метод. Устанавливает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A в C++."
type: docs
weight: 2000
url: /ru/cpp/aspose.pdf.lowcode/pdfaoptionsbase/set_excludefontsstrategy/
---
## PdfAOptionsBase::set_ExcludeFontsStrategy method


Устанавливает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A.

```cpp
void Aspose::Pdf::LowCode::PdfAOptionsBase::set_ExcludeFontsStrategy(PdfFormatConversionOptions::RemoveFontsStrategy value)
```

## Примечания


Стратегия удаления шрифтов. Это может быть одно из значений перечисления [PdfFormatConversionOptions::RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/). По умолчанию используется комбинация [PdfFormatConversionOptions::RemoveFontsStrategy::SubsetFonts](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/) и [PdfFormatConversionOptions::RemoveFontsStrategy::RemoveDuplicatedFonts](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/).

Это свойство позволяет управлять тем, как шрифты обрабатываются во время процесса конвертации. Вы можете выбрать удаление дублированных шрифтов, удаление похожих шрифтов с разной шириной или подмножество шрифтов.
## См. также

* Enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/)
* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
