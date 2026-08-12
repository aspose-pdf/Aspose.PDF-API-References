---
title: "Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode перечисление"
linktitle: "TextFormattingMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode перечисление. Определяет различные режимы, которые могут использоваться при преобразовании PDF‑документа в текст. См. класс TextDevice в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.text/textextractionoptions/textformattingmode/
---
## TextFormattingMode enum


Определяет различные режимы, которые могут использоваться при преобразовании PDF‑документа в текст. Смотрите класс [TextDevice](../).

```cpp
enum class TextFormattingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Pure | 0 | Представляет содержимое PDF с небольшим набором процедур форматирования. |
| Raw | 1 | Отображать содержимое PDF как есть, то есть без форматирования. |
| Flatten | 2 | Отображать содержимое PDF с позиционированием текстовых фрагментов по их координатам. По сути это аналог режима "Raw". Но в то время как "Raw" сосредоточен на сохранении структуры текстовых фрагментов (операторов) в документе, "Flatten" ориентирован на сохранение текста в порядке его чтения. |
| Экономия памяти | 3 | Извлечение с экономией памяти. Это почти то же самое, что режим 'Raw', но работает немного быстрее и использует меньше памяти. |

## См. также

* Class [TextExtractionOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
