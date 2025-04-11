---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Некоторые PDF-документы содержат специальные символы юникода, которые принадлежат области частного использования (PUA), см. описание на https//en.wikipedia.org/wiki/Private_Use_Areas. Эти символы вызывают ошибки соответствия PDF/A, такие как "Текст сопоставлен с областью частного использования юникода, но запись ActualText отсутствует". Эта перечисление объявляет стратегии, которые могут быть использованы для обработки символов PUA.
type: docs
weight: 8390
url: /ru/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## Перечисление PdfFormatConversionOptions.PuaProcessingStrategy

Некоторые PDF-документы содержат специальные символы юникода, которые принадлежат области частного использования (PUA), см. описание на https://en.wikipedia.org/wiki/Private_Use_Areas. Эти символы вызывают ошибки соответствия PDF/A, такие как "Текст сопоставлен с областью частного использования юникода, но запись ActualText отсутствует". Эта перечисление объявляет стратегии, которые могут быть использованы для обработки символов PUA.

```csharp
public enum PuaProcessingStrategy
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Отключить обработку символов PUA. Эта стратегия используется по умолчанию для документов PDF/A с соответствием уровня B. |
| SurroundPuaTextWithEmptyActualText | `1` | Вставляет отмеченный блок содержимого с записью ActualText, которая содержит пустой текст. Эта стратегия дает хорошие результаты для документов без отмеченных блоков содержимого. Используется по умолчанию для документов PDF/A с соответствием уровня A. |
| SubstitutePuaSymbols | `2` | Эта стратегия работает медленнее, чем 'SurroundPuaTextWithEmptyActualText', но она может устранить ошибки соответствия PUA для документов, которые не могут быть правильно обработаны SurroundPuaTextWithEmptyActualText. Символы PUA заменяются на символ 'пробел' или специальный юникод (некоторые символы PUA имеют юникодные аналоги). Замена применяется не к тексту документа, а к внутренним данным шрифта ToUnicode, поэтому это не влияет на видимость символа, но влияет на представление символа в буфере обмена при операции копирования/вставки. |

### См. также

* класс [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)