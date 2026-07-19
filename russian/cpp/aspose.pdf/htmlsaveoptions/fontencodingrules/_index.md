---
title: "Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum"
linktitle: "FontEncodingRules"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum. Это перечисление определяет правила, которые настраивают логику кодирования в C++."
type: docs
weight: 5200
url: /ru/cpp/aspose.pdf/htmlsaveoptions/fontencodingrules/
---
## FontEncodingRules enum


Это перечисление определяет правила, которые настраивают логику кодирования.

```cpp
enum class FontEncodingRules : uint8_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | 0 | Оставить логику кодирования «как есть» — в соответствии со спецификацией PDF. |
| DecreaseToUnicodePriorityLevel | 1 | ToUnicode — это специальный механизм, который помогает декодировать входные коды в символы Unicode. Согласно спецификации, он должен использоваться в качестве первого механизма для получения символов Unicode для конкретного входного кода. Однако в некоторых документах используются нестандартные шрифты, и для корректного преобразования этих документов может потребоваться уменьшить приоритет ToUnicode и использовать другие механизмы декодирования входных кодов. |

## См. также

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
