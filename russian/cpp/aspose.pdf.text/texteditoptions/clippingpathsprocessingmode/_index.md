---
title: "Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum"
linktitle: "ClippingPathsProcessingMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum. Режимы обработки обрезающих путей в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.text/texteditoptions/clippingpathsprocessingmode/
---
## ClippingPathsProcessingMode enum


Режимы обработки обрезающих путей.

```cpp
enum class ClippingPathsProcessingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| KeepIntact | 0 | Сохраняет обрезающие пути оригинального макета страницы. (По умолчанию) |
| Expand | 1 | Оригинальный обрезающий путь будет расширен, если отредактированный текст требует больше места. |
| Remove | 2 | Оригинальный обрезающий путь будет удалён, если отредактированный текст требует больше места. Внимание: поскольку обрезающие пути могут взаимодействовать друг с другом, их удаление может привести к неожиданным результатам в макете страницы. |

## См. также

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
