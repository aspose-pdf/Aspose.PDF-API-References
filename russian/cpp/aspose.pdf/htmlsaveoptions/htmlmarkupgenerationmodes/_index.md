---
title: "Aspose::Pdf::HtmlSaveOptions::HtmlMarkupGenerationModes enum"
linktitle: "HtmlMarkupGenerationModes"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HtmlSaveOptions::HtmlMarkupGenerationModes enum. Иногда присутствуют специфические требования к создаваемому HTML. Это перечисление определяет режимы подготовки HTML, которые могут использоваться при конвертации PDF в HTML для соответствия таким специфическим требованиям в C++."
type: docs
weight: 5500
url: /ru/cpp/aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmodes/
---
## HtmlMarkupGenerationModes enum


Иногда присутствуют специфические требования к создаваемому HTML. Этот enum определяет режимы подготовки HTML, которые могут использоваться при конвертации PDF в HTML для соответствия таким специфическим требованиям.

```cpp
enum class HtmlMarkupGenerationModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| WriteAllHtml | 0 | Режим по умолчанию, когда специфические требования отсутствуют. Будет сгенерирован вывод, содержащий все части HTML без какой-либо дополнительной обработки. |
| WriteOnlyBodyContent | 1 | будет удалено всё HTML‑содержимое, находящееся за пределами тела HTML, то есть останется только содержимое, находящееся внутри тегов **<body>****</body>**. |

## См. также

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
