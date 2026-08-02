---
title: "Перечисление PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Некоторые PDF‑документы содержат специальные символы Unicode, принадлежащие Private Use Area (PUA); см. описание по адресу https//en.wikipedia.org/wiki/Private_Use_Areas. Эти символы вызывают ошибки соответствия PDF/A, такие как «Текст сопоставлен с Unicode Private Use Area, но запись ActualText отсутствует». Это перечисление объявляет стратегии, которые можно использовать для обработки символов PUA."
type: docs
weight: 8530
url: /ru/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Некоторые PDF‑документы содержат специальные символы Unicode, принадлежащие Private Use Area (PUA); см. описание по адресу https://en.wikipedia.org/wiki/Private_Use_Areas. Эти символы вызывают ошибки соответствия PDF/A, такие как "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Это перечисление объявляет стратегии, которые можно использовать для обработки символов PUA.

```csharp
public enum PuaProcessingStrategy
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Отключить обработку символов PUA. Эта стратегия используется по умолчанию для PDF/A‑документов с уровнем соответствия B. |
| SurroundPuaTextWithEmptyActualText | `1` | Вставляет блок помеченного содержимого с записью ActualText, содержащей пустой текст. Эта стратегия дает хорошие результаты для документов без блоков помеченного содержимого. По умолчанию используется для PDF/A‑документов с уровнем соответствия A. |
| SubstitutePuaSymbols | `2` | Эта стратегия работает медленнее, чем 'SurroundPuaTextWithEmptyActualText', но может устранять ошибки соответствия PUA для документов, которые нельзя корректно обработать с помощью SurroundPuaTextWithEmptyActualText. Символы PUA заменяются символом 'space' или специальным Unicode (у некоторых символов PUA есть аналогичные Unicode). Замена применяется не к тексту документа, а к внутренним данным шрифта ToUnicode, поэтому она не влияет на визуальное отображение символа, но влияет на его представление при операции копирования/вставки в системный буфер. |

### См. также

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


