---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode enum. Определяет различные режимы, которые могут быть использованы при преобразовании pdf-документа в текст. См. класс TextDevice
type: docs
weight: 10900
url: /ru/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode перечисление

Определяет различные режимы, которые могут быть использованы при преобразовании pdf-документа в текст. См. класс !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Pure | `0` | Представляет содержимое pdf с некоторыми форматирующими процедурами. |
| Raw | `1` | Представляет содержимое pdf как есть, т.е. без форматирования. |
| Flatten | `2` | Представляет содержимое pdf с позиционированием текстовых фрагментов по их координатам. Это в основном похоже на режим "Raw". Но в то время как "Raw" сосредоточен на сохранении структуры текстовых фрагментов (операторов) в документе, "Flatten" сосредоточен на сохранении текста в порядке его чтения. |
| MemorySaving | `3` | Извлечение с экономией памяти. Это почти то же самое, что и режим 'Raw', но работает немного быстрее и использует меньше памяти. |

### См. также

* класс [TextExtractionOptions](../textextractionoptions/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)