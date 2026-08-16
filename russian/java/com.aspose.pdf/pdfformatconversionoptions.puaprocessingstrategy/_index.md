---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Справочник API Aspose.PDF для Java"
description: "Некоторые PDF‑документы содержат специальные юникод‑символы, принадлежащие области частного использования (PUA), см. описание по адресу https://en.wikipedia.org/wiki/Private_Use_Areas. Эти символы."
type: docs
weight: 3750
url: /ru/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Некоторые PDF‑документы содержат специальные юникод‑символы, принадлежащие области частного использования (PUA), см. описание по адресу https://en.wikipedia.org/wiki/Private_Use_Areas. Эти символы вызывают ошибки соответствия PDF/A, например "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Эта перечисление объявляет стратегии, которые можно использовать для обработки символов PUA.

## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Отключить обработку символов PUA. Эта стратегия используется по умолчанию для PDF/A‑документов с уровнем соответствия B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Эта стратегия работает медленнее, чем 'SurroundPuaTextWithEmptyActualText', но может удалять ошибки соответствия PUA для документов, которые нельзя корректно обработать с помощью SurroundPuaTextWithEmptyActualText. Символы PUA заменяются символом 'space' или специальным юникодом (у некоторых символов PUA есть аналогичные юникод‑символы). Замена применяется не к тексту документа, а к внутренним данным шрифта ToUnicode, поэтому она не влияет на визуальное отображение символа, но влияет на его представление при копировании/вставке в буфер системы. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Вставляет блок помеченного содержимого с записью ActualText, содержащей пустой текст. Эта стратегия дает хорошие результаты для документов без блоков помеченного содержимого. Используется по умолчанию для PDF/A‑документов с уровнем соответствия A. |

### None {#None}
```
public static final int None
```

Отключить обработку символов PUA. Эта стратегия используется по умолчанию для PDF/A‑документов с уровнем соответствия B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Эта стратегия работает медленнее, чем 'SurroundPuaTextWithEmptyActualText', но может удалять ошибки соответствия PUA для документов, которые нельзя корректно обработать с помощью SurroundPuaTextWithEmptyActualText. Символы PUA заменяются символом 'space' или специальным юникодом (у некоторых символов PUA есть аналогичные юникод‑символы). Замена применяется не к тексту документа, а к внутренним данным шрифта ToUnicode, поэтому она не влияет на визуальное отображение символа, но влияет на его представление при копировании/вставке в буфер системы.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Вставляет блок помеченного содержимого с записью ActualText, содержащей пустой текст. Эта стратегия дает хорошие результаты для документов без блоков помеченного содержимого. Используется по умолчанию для PDF/A‑документов с уровнем соответствия A.
