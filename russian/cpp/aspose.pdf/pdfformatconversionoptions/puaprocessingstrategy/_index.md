---
title: "Перечисление Aspose::Pdf::PdfFormatConversionOptions::PuaProcessingStrategy"
linktitle: "PuaProcessingStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление Aspose::Pdf::PdfFormatConversionOptions::PuaProcessingStrategy. Некоторые PDF‑документы содержат специальные символы Unicode, принадлежащие Private Use Area (PUA), см. описание по ссылке . Эти символы вызывают ошибки соответствия PDF/A, такие как \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Это перечисление объявляет стратегии, которые можно использовать для обработки символов PUA в C++."
type: docs
weight: 4200
url: /ru/cpp/aspose.pdf/pdfformatconversionoptions/puaprocessingstrategy/
---
## PuaProcessingStrategy enum


Некоторые PDF‑документы содержат специальные юникод‑символы, принадлежащие к Private Use Area (PUA); см. описание по ссылке [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). Эти символы вызывают ошибки соответствия PDF/A, такие как \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Эта перечисление объявляет стратегии, которые можно использовать для обработки символов PUA.

```cpp
enum class PuaProcessingStrategy
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Отключить обработку символов PUA. Эта стратегия используется по умолчанию для PDF/A‑документов с уровнем соответствия B. |
| SurroundPuaTextWithEmptyActualText | 1 | Вставляет блок помеченного контента с записью ActualText, содержащей пустой текст. Эта стратегия дает хорошие результаты для документов без блоков помеченного контента. По умолчанию используется для PDF/A‑документов с уровнем соответствия A. |
| SubstitutePuaSymbols | 2 | Эта стратегия работает медленнее, чем 'SurroundPuaTextWithEmptyActualText', но может устранять ошибки соответствия PUA для документов, которые нельзя корректно обработать с помощью SurroundPuaTextWithEmptyActualText. Символы PUA заменяются символом пробела или специальным Unicode (у некоторых символов PUA есть аналогичные Unicode). Замена применяется не к тексту документа, а к внутренним данным шрифта ToUnicode, поэтому она не влияет на визуальное отображение символа, но влияет на его представление при копировании/вставке в буфер системы. |

## См. также

* Class [PdfFormatConversionOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
